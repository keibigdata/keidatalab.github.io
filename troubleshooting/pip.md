### refers 'http://docs.python-guide.org/en/latest/dev/virtualenvs/'
  
kjhan@DataLX01:~$ which pip3
~~~
/usr/bin/pip3
~~~
kjhan@DataLX01:~$ pip3 install --user pipenv
~~~
Collecting pipenv
  Downloading pipenv-11.5.2.tar.gz (3.9MB)
    100% |████████████████████████████████| 3.9MB 494kB/s 
Collecting pip>=9.0.1 (from pipenv)
  Downloading pip-9.0.1-py2.py3-none-any.whl (1.3MB)
    100% |████████████████████████████████| 1.3MB 1.4MB/s 
Collecting setuptools>=36.2.1 (from pipenv)
  Downloading setuptools-38.5.2-py2.py3-none-any.whl (490kB)
    100% |████████████████████████████████| 491kB 3.0MB/s 
Collecting virtualenv (from pipenv)
  Downloading virtualenv-15.1.0-py2.py3-none-any.whl (1.8MB)
    100% |████████████████████████████████| 1.8MB 1.0MB/s 
Collecting virtualenv-clone>=0.2.5 (from pipenv)
  Downloading virtualenv_clone-0.3.0-py2.py3-none-any.whl
Collecting pathlib; python_version < "3.4" (from pipenv)
  Downloading pathlib-1.0.1.tar.gz (49kB)
    100% |████████████████████████████████| 51kB 7.4MB/s 
Collecting requests[security]; python_version < "3.0" (from pipenv)
  Downloading requests-2.18.4-py2.py3-none-any.whl (88kB)
    100% |████████████████████████████████| 92kB 8.1MB/s 
Collecting ordereddict; python_version < "3.0" (from pipenv)
  Downloading ordereddict-1.1.tar.gz
Collecting idna<2.7,>=2.5 (from requests[security]; python_version < "3.0"->pipenv)
  Downloading idna-2.6-py2.py3-none-any.whl (56kB)
    100% |████████████████████████████████| 61kB 8.3MB/s 
Collecting certifi>=2017.4.17 (from requests[security]; python_version < "3.0"->pipenv)
  Downloading certifi-2018.1.18-py2.py3-none-any.whl (151kB)
    100% |████████████████████████████████| 153kB 6.5MB/s 
Collecting chardet<3.1.0,>=3.0.2 (from requests[security]; python_version < "3.0"->pipenv)
  Downloading chardet-3.0.4-py2.py3-none-any.whl (133kB)
    100% |████████████████████████████████| 143kB 6.9MB/s 
Collecting urllib3<1.23,>=1.21.1 (from requests[security]; python_version < "3.0"->pipenv)
  Downloading urllib3-1.22-py2.py3-none-any.whl (132kB)
    100% |████████████████████████████████| 133kB 6.3MB/s 
Collecting cryptography>=1.3.4; extra == "security" (from requests[security]; python_version < "3.0"->pipenv)
  Downloading cryptography-2.1.4-cp35-cp35m-manylinux1_x86_64.whl (2.2MB)
    100% |████████████████████████████████| 2.2MB 707kB/s 
Collecting pyOpenSSL>=0.14; extra == "security" (from requests[security]; python_version < "3.0"->pipenv)
  Downloading pyOpenSSL-17.5.0-py2.py3-none-any.whl (53kB)
    100% |████████████████████████████████| 61kB 9.0MB/s 
Collecting cffi>=1.7; platform_python_implementation != "PyPy" (from cryptography>=1.3.4; extra == "security"->requests[security]; python_version < "3.0"->pipenv)
  Downloading cffi-1.11.5-cp35-cp35m-manylinux1_x86_64.whl (420kB)
    100% |████████████████████████████████| 430kB 3.6MB/s 
Collecting six>=1.4.1 (from cryptography>=1.3.4; extra == "security"->requests[security]; python_version < "3.0"->pipenv)
  Downloading six-1.11.0-py2.py3-none-any.whl
Collecting asn1crypto>=0.21.0 (from cryptography>=1.3.4; extra == "security"->requests[security]; python_version < "3.0"->pipenv)
  Downloading asn1crypto-0.24.0-py2.py3-none-any.whl (101kB)
    100% |████████████████████████████████| 102kB 7.5MB/s 
Collecting pycparser (from cffi>=1.7; platform_python_implementation != "PyPy"->cryptography>=1.3.4; extra == "security"->requests[security]; python_version < "3.0"->pipenv)
  Downloading pycparser-2.18.tar.gz (245kB)
    100% |████████████████████████████████| 256kB 4.7MB/s 
Building wheels for collected packages: pipenv, pathlib, ordereddict, pycparser
  Running setup.py bdist_wheel for pipenv ... done
  Stored in directory: /home/kjhan/.cache/pip/wheels/9f/7a/8a/e89a935da667341406e1e819ce80a8d51749e58fae65341744
  Running setup.py bdist_wheel for pathlib ... done
  Stored in directory: /home/kjhan/.cache/pip/wheels/2a/23/a5/d8803db5d631e9f391fe6defe982a238bf5483062eeb34e841
  Running setup.py bdist_wheel for ordereddict ... done
  Stored in directory: /home/kjhan/.cache/pip/wheels/cf/2c/b5/a1bfd8848f7861c1588f1a2dfe88c11cf3ab5073ab7af08bc9
  Running setup.py bdist_wheel for pycparser ... done
  Stored in directory: /home/kjhan/.cache/pip/wheels/95/14/9a/5e7b9024459d2a6600aaa64e0ba485325aff7a9ac7489db1b6
Successfully built pipenv pathlib ordereddict pycparser
Installing collected packages: pip, setuptools, virtualenv, virtualenv-clone, pathlib, idna, certifi, chardet, urllib3, pycparser, cffi, six, asn1crypto, cryptography, pyOpenSSL, requests, ordereddict, pipenv
Successfully installed asn1crypto certifi cffi chardet-2.3.0 cryptography-1.2.3 idna-2.0 ordereddict pathlib pip-8.1.1 pipenv pyOpenSSL pycparser requests-2.9.1 setuptools-20.7.0 six-1.10.0 urllib3-1.13.1 virtualenv-15.0.1 virtualenv-clone
You are using pip version 8.1.1, however version 9.0.1 is available.
You should consider upgrading via the 'pip install --upgrade pip' command.
~~~
kjhan@DataLX01:~$ which pip
~~~
/home/kjhan/.local/bin/pip
~~~
kjhan@DataLX01:~$ pip install --upgrade pip
~~~
Requirement already up-to-date: pip in ./.local/lib/python3.5/site-packages
~~~
kjhan@DataLX01:~$ which pip3
~~~
/home/kjhan/.local/bin/pip3
~~~
kjhan@DataLX01:~$ pip install --user pipenv
~~~
Requirement already satisfied: pipenv in ./.local/lib/python3.5/site-packages
Requirement already satisfied: pathlib in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: setuptools>=36.2.1 in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: virtualenv in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: requests[security] in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: pip>=9.0.1 in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: ordereddict in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: virtualenv-clone>=0.2.5 in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: chardet<3.1.0,>=3.0.2 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: certifi>=2017.4.17 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: urllib3<1.23,>=1.21.1 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: idna<2.7,>=2.5 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: pyOpenSSL>=0.14; extra == "security" in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: cryptography>=1.3.4; extra == "security" in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: six>=1.5.2 in ./.local/lib/python3.5/site-packages (from pyOpenSSL>=0.14; extra == "security"->requests[security]->pipenv)
Requirement already satisfied: asn1crypto>=0.21.0 in ./.local/lib/python3.5/site-packages (from cryptography>=1.3.4; extra == "security"->requests[security]->pipenv)
Requirement already satisfied: cffi>=1.7; platform_python_implementation != "PyPy" in ./.local/lib/python3.5/site-packages (from cryptography>=1.3.4; extra == "security"->requests[security]->pipenv)
Requirement already satisfied: pycparser in ./.local/lib/python3.5/site-packages (from cffi>=1.7; platform_python_implementation != "PyPy"->cryptography>=1.3.4; extra == "security"->requests[security]->pipenv)
~~~
kjhan@DataLX01:~$ pip3 install --user pipenv
~~~
Requirement already satisfied: pipenv in ./.local/lib/python3.5/site-packages
Requirement already satisfied: ordereddict in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: pathlib in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: requests[security] in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: virtualenv-clone>=0.2.5 in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: virtualenv in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: pip>=9.0.1 in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: setuptools>=36.2.1 in ./.local/lib/python3.5/site-packages (from pipenv)
Requirement already satisfied: chardet<3.1.0,>=3.0.2 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: idna<2.7,>=2.5 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: urllib3<1.23,>=1.21.1 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: certifi>=2017.4.17 in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: cryptography>=1.3.4; extra == "security" in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: pyOpenSSL>=0.14; extra == "security" in ./.local/lib/python3.5/site-packages (from requests[security]->pipenv)
Requirement already satisfied: six>=1.4.1 in ./.local/lib/python3.5/site-packages (from cryptography>=1.3.4; extra == "security"->requests[security]->pipenv)
Requirement already satisfied: asn1crypto>=0.21.0 in ./.local/lib/python3.5/site-packages (from cryptography>=1.3.4; extra == "security"->requests[security]->pipenv)
Requirement already satisfied: cffi>=1.7; platform_python_implementation != "PyPy" in ./.local/lib/python3.5/site-packages (from cryptography>=1.3.4; extra == "security"->requests[security]->pipenv)
Requirement already satisfied: pycparser in ./.local/lib/python3.5/site-packages (from cffi>=1.7; platform_python_implementation != "PyPy"->cryptography>=1.3.4; extra == "security"->requests[security]->pipenv)
~~~
kjhan@DataLX01:~$ cd .local/bin  
kjhan@DataLX01:~/.local/bin$ ls -al
~~~
합계 52
drwxrwxr-x 2 kjhan kjhan 4096  3월 12 09:54 .
drwx------ 4 kjhan kjhan 4096  3월 12 09:54 ..
-rwxrwxr-x 1 kjhan kjhan  224  3월 12 09:54 chardetect
-rwxrwxr-x 1 kjhan kjhan  233  3월 12 09:54 easy_install
-rwxrwxr-x 1 kjhan kjhan  233  3월 12 09:54 easy_install-3.5
-rwxrwxr-x 1 kjhan kjhan  222  3월 12 09:54 pewtwo
-rwxrwxr-x 1 kjhan kjhan  205  3월 12 09:54 pip
-rwxrwxr-x 1 kjhan kjhan  205  3월 12 09:54 pip3
-rwxrwxr-x 1 kjhan kjhan  205  3월 12 09:54 pip3.5
-rwxrwxr-x 1 kjhan kjhan  206  3월 12 09:54 pipenv
-rwxrwxr-x 1 kjhan kjhan  217  3월 12 09:54 pipenv-resolver
-rwxrwxr-x 1 kjhan kjhan  212  3월 12 09:54 virtualenv
-rwxrwxr-x 1 kjhan kjhan  217  3월 12 09:54 virtualenv-clone
~~~
kjhan@DataLX01:~$ mkdir projectPipenv  
kjhan@DataLX01:~$ cd projectPipenv/  
kjhan@DataLX01:~/projectPipenv$ pipenv install requests
~~~
Creating a virtualenv for this project…
Using /usr/bin/python3 (3.5.2) to create virtualenv…
⠋Already using interpreter /usr/bin/python3
Using base prefix '/usr'
New python executable in /home/kjhan/.local/share/virtualenvs/projectPipenv-EY907GBp/bin/python3
Also creating executable in /home/kjhan/.local/share/virtualenvs/projectPipenv-EY907GBp/bin/python
Installing setuptools, pip, wheel...done.

Virtualenv location: /home/kjhan/.local/share/virtualenvs/projectPipenv-EY907GBp
Creating a Pipfile for this project…
Installing requests…
Collecting requests
  Using cached requests-2.18.4-py2.py3-none-any.whl
Installing collected packages: requests
Successfully installed requests-2.18.4

Adding requests to Pipfile's [packages]…
Pipfile.lock not found, creating…
Locking [dev-packages] dependencies…
Locking [packages] dependencies…
Updated Pipfile.lock (23c00a)!
Installing dependencies from Pipfile.lock (23c00a)…
     ▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉▉ 5/5 — 00:00:00
To activate this project's virtualenv, run the following:
 $ pipenv shell
~~~
kjhan@DataLX01:~/projectPipenv$ emacs main.py
~~~
import requests

response = requests.get('https://httpbin.org/ip')
print("Your IP is {0}".format(response.json()['origin']))
~~~
kjhan@DataLX01:~/projectPipenv$ pipenv run python main.py
~~~
Your IP is 203.250.98.129
~~~
kjhan@DataLX01:~/projectPipenv$ pipenv run python3 main.py
~~~
Your IP is 203.250.98.129
~~~
