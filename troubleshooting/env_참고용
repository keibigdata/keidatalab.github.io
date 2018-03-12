### 기본 라이브러리 설치
~~~
sudo apt-get install -y make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev
~~~

    
### Pyenv

pyenv의 기능은 github 홈페이지 README 문서에서 아래와 같이 소개하고 있다.  

* 시스템 전역 파이썬 버전을 변경할 수 있다.
* 프로젝트별 파이썬 버전을 지정할 수 있다.
* 환경변수로 파이썬 버전을 지정할 수 있다.
* 동시에 여러 버전의 파이썬을 찾을 수 있다. tox 유틸리티와 결합하여 빌드 호환성 체크에 유용하다.  //

#### 일반 설치
~~~
git clone https://github.com/pyenv/pyenv.git ~/.pyenv
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(pyenv init -)"' >> ~/.bash_profile
~~~

#### 서버 설치 및 세팅

~~~
git clone https://github.com/pyenv/pyenv.git /usr/share/.pyenv
~~~

/etc/bash.bashrc에 추가
```
export PYENV_ROOT="/usr/share/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

```
$ pyenv install --list # 설치 가능한 패키지 목록 (파이썬 버전별 목록)
$ pyenv install 3.6.0 
```


### pyenv-virtualenv
#### 일반 세팅

```
$ git clone https://github.com/yyuu/pyenv-virtualenv.git ~/.pyenv/plugins/pyenv-virtualenv

echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.bash_profile
source ~/.bash_profile
```

#### 서버 세팅
```
$ git clone https://github.com/yyuu/pyenv-virtualenv.git /usr/share/.pyenv/plugins/pyenv-virtualenv
```

/etc/bash.bashrc에 추가
```
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

```
$ pyenv virtualenv 3.5.2 test
$ pyenv versions
$ pyenv activate test
$ pyenv deactivate
```

#### Jupyter notebook 세팅
```
$ pip install jupyter notebook
$ jupyter notebook --generate-config
```

Hash Password 준비
``` 
from notebook.auth import passwd

passwd()
Enter password: 
Verify password: 
Out[2]: 'sha1:f24baff49ac5:863dd2ae747212ede58125302d227f0ca7b12bb3'

```

jupyter notebook list를 이용


~/.jupyter/jupyter_notebook_config.py 설정
```
c.NotebookApp.password =
u'sha1:f24baff49ac5:863dd2ae747212ede58125302d227f0ca7b12bb3


# The IP address the notebook server will listen on.
# c.NotebookApp.ip = 'localhost'
c.NotebookApp.ip = '192.168.174.131'
# c.NotebookApp.port_retries = 50
c.NotebookApp.port_retries = 8888
]
```
