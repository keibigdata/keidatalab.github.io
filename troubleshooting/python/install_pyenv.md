envtester@DataLX01:~$ which pip
~~~
/usr/local/bin/pip
~~~
envtester@DataLX01:~$ which virtualenv
~~~
/usr/bin/virtualenv
~~~
envtester@DataLX01:~$ virtualenv myTF
~~~
Running virtualenv with interpreter /usr/bin/python2
New python executable in /home/envtester/myTF/bin/python2
Also creating executable in /home/envtester/myTF/bin/python
Installing setuptools, pkg_resources, pip, wheel...done.
~~~
envtester@DataLX01:~$ cd myTF/bin
envtester@DataLX01:~/myTF/bin$ ls -al act*
~~~
-rw-rw-r-- 1 envtester envtester 2079  3월 19 16:09 activate
-rw-rw-r-- 1 envtester envtester 1021  3월 19 16:09 activate.csh
-rw-rw-r-- 1 envtester envtester 2219  3월 19 16:09 activate.fish
-rw-rw-r-- 1 envtester envtester 1137  3월 19 16:09 activate_this.py
~~~
envtester@DataLX01:~/myTF/bin$ chmod 700 activate
envtester@DataLX01:~/myTF/bin$ cd
~~~
