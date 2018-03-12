kjhan@DataLX01:~$ mkdir projectVirtualenv  
kjhan@DataLX01:~$ cd projectVirtualenv/  
kjhan@DataLX01:~/projectVirtualenv$ which virtualenv  
~~~
/home/kjhan/.local/bin/virtualenv
~~~
kjhan@DataLX01:~/projectVirtualenv$ virtualenv
~~~
Running virtualenv with interpreter /usr/bin/python2
You must provide a DEST_DIR
Usage: virtualenv.py [OPTIONS] DEST_DIR

Options:
  --version             show program's version number and exit
  -h, --help            show this help message and exit
  -v, --verbose         Increase verbosity.
  -q, --quiet           Decrease verbosity.
  -p PYTHON_EXE, --python=PYTHON_EXE
                        The Python interpreter to use, e.g.,
                        --python=python2.5 will use the python2.5 interpreter
                        to create the new environment.  The default is the
                        python2 interpreter on your path (e.g.
                        /usr/bin/python2)
  --clear               Clear out the non-root install and start from scratch.
  --no-site-packages    DEPRECATED. Retained only for backward compatibility.
                        Not having access to global site-packages is now the
                        default behavior.
  --system-site-packages
                        Give the virtual environment access to the global
                        site-packages.
  --always-copy         Always copy files rather than symlinking.
  --unzip-setuptools    Unzip Setuptools when installing it.
  --relocatable         Make an EXISTING virtualenv environment relocatable.
                        This fixes up scripts and makes all .pth files
                        relative.
  --no-setuptools       Do not install setuptools in the new virtualenv.
  --no-pip              Do not install pip in the new virtualenv.
  --no-wheel            Do not install wheel in the new virtualenv.
  --extra-search-dir=DIR
                        Directory to look for setuptools/pip distributions in.
                        This option can be used multiple times.
  --download            Download preinstalled packages from PyPI.
  --no-download, --never-download
                        Do not download preinstalled packages from PyPI.
  --prompt=PROMPT       Provides an alternative prompt prefix for this
                        environment.
  --setuptools          DEPRECATED. Retained only for backward compatibility.
                        This option has no effect.
  --distribute          DEPRECATED. Retained only for backward compatibility.
                        This option has no effect.
~~~
kjhan@DataLX01:~/projectVirtualenv$ virtualenv --version
~~~
15.0.1
~~~
kjhan@DataLX01:~/projectVirtualenv$ which virtualenv
~~~
/home/kjhan/.local/bin/virtualenv
~~~
kjhan@DataLX01:~/projectVirtualenv$ virtualenv projVirtualenv
~~~
Running virtualenv with interpreter /usr/bin/python2
New python executable in /home/kjhan/projectVirtualenv/projVirtualenv/bin/python2
Also creating executable in /home/kjhan/projectVirtualenv/projVirtualenv/bin/python
Installing setuptools, pkg_resources, pip, wheel...done.
~~~
kjhan@DataLX01:~/projectVirtualenv$ virtualenv -p /usr/bin/python3.5 projVirtualenv
~~~
Running virtualenv with interpreter /usr/bin/python3.5
Using base prefix '/usr'
New python executable in /home/kjhan/projectVirtualenv/projVirtualenv/bin/python3.5
Not overwriting existing python script /home/kjhan/projectVirtualenv/projVirtualenv/bin/python (you must use /home/kjhan/projectVirtualenv/projVirtualenv/bin/python3.5)
Installing setuptools, pkg_resources, pip, wheel...done.
~~~
kjhan@DataLX01:~/projectVirtualenv$ pip list
~~~
DEPRECATION: The default format will switch to columns in the future. You can use --format=(legacy|columns) (or define a format=(legacy|columns) in your pip.conf under the [list] section) to disable this warning.
apturl (0.5.2)
beautifulsoup4 (4.4.1)
blinker (1.3)
Brlapi (0.6.4)
chardet (2.3.0)
checkbox-support (0.22)
command-not-found (0.3)
cryptography (1.2.3)
decorator (4.0.6)
defer (1.0.6)
feedparser (5.1.3)
guacamole (0.9.2)
html5lib (0.999)
httplib2 (0.9.1)
idna (2.0)
Jinja2 (2.8)
language-selector (0.1)
louis (2.6.4)
lxml (3.5.0)
Mako (1.0.3)
MarkupSafe (0.23)
numpy (1.11.0)
oauthlib (1.0.3)
onboard (1.2.0)
padme (1.1.1)
pexpect (4.0.1)
Pillow (3.1.2)
pip (9.0.1)
plainbox (0.25)
ptyprocess (0.5)
pyasn1 (0.1.9)
pycups (1.9.73)
pycurl (7.43.0)
pygobject (3.20.0)
PyJWT (1.3.0)
pyparsing (2.0.3)
python-apt (1.1.0b1+ubuntu0.16.4.1)
python-debian (0.1.27)
python-systemd (231)
pyxdg (0.25)
reportlab (3.3.0)
requests (2.9.1)
scipy (0.17.0)
screen-resolution-extra (0.0.0)
sessioninstaller (0.0.0)
setuptools (20.7.0)
six (1.10.0)
ssh-import-id (5.5)
system-service (0.3)
ubuntu-drivers-common (0.0.0)
ufw (0.35)
unattended-upgrades (0.1)
unity-scope-calculator (0.1)
unity-scope-chromiumbookmarks (0.1)
unity-scope-colourlovers (0.1)
unity-scope-devhelp (0.1)
unity-scope-firefoxbookmarks (0.1)
unity-scope-gdrive (0.7)
unity-scope-manpages (0.1)
unity-scope-openclipart (0.1)
unity-scope-texdoc (0.1)
unity-scope-tomboy (0.1)
unity-scope-virtualbox (0.1)
unity-scope-yelp (0.1)
unity-scope-zotero (0.1)
urllib3 (1.13.1)
usb-creator (0.3.0)
virtualenv (15.0.1)
wheel (0.29.0)
xdiagnose (3.8.4.1)
xkit (0.0.0)
XlsxWriter (0.7.3)
~~~
kjhan@DataLX01:~/projectVirtualenv$ pip install --user jupyter
~~~
Collecting jupyter
  Using cached jupyter-1.0.0-py2.py3-none-any.whl
Collecting nbconvert (from jupyter)
  Using cached nbconvert-5.3.1-py2.py3-none-any.whl
Collecting ipykernel (from jupyter)
  Using cached ipykernel-4.8.2-py3-none-any.whl
Collecting qtconsole (from jupyter)
  Using cached qtconsole-4.3.1-py2.py3-none-any.whl
Collecting notebook (from jupyter)
  Using cached notebook-5.4.0-py2.py3-none-any.whl
Collecting ipywidgets (from jupyter)
  Using cached ipywidgets-7.1.2-py2.py3-none-any.whl
Collecting jupyter-console (from jupyter)
  Using cached jupyter_console-5.2.0-py2.py3-none-any.whl
Requirement already satisfied: jinja2 in /usr/lib/python3/dist-packages (from nbconvert->jupyter)
Collecting jupyter-core (from nbconvert->jupyter)
  Using cached jupyter_core-4.4.0-py2.py3-none-any.whl
Collecting nbformat>=4.4 (from nbconvert->jupyter)
  Using cached nbformat-4.4.0-py2.py3-none-any.whl
Collecting traitlets>=4.2 (from nbconvert->jupyter)
  Using cached traitlets-4.3.2-py2.py3-none-any.whl
Collecting mistune>=0.7.4 (from nbconvert->jupyter)
  Using cached mistune-0.8.3-py2.py3-none-any.whl
Collecting pandocfilters>=1.4.1 (from nbconvert->jupyter)
Collecting testpath (from nbconvert->jupyter)
  Using cached testpath-0.3.1-py2.py3-none-any.whl
Collecting bleach (from nbconvert->jupyter)
  Using cached bleach-2.1.3-py2.py3-none-any.whl
Collecting pygments (from nbconvert->jupyter)
  Using cached Pygments-2.2.0-py2.py3-none-any.whl
Collecting entrypoints>=0.2.2 (from nbconvert->jupyter)
  Using cached entrypoints-0.2.3-py2.py3-none-any.whl
Collecting tornado>=4.0 (from ipykernel->jupyter)
Collecting ipython>=4.0.0 (from ipykernel->jupyter)
  Using cached ipython-6.2.1-py3-none-any.whl
Collecting jupyter-client (from ipykernel->jupyter)
  Using cached jupyter_client-5.2.2-py2.py3-none-any.whl
Collecting ipython-genutils (from qtconsole->jupyter)
  Using cached ipython_genutils-0.2.0-py2.py3-none-any.whl
Collecting terminado>=0.8.1 (from notebook->jupyter)
  Using cached terminado-0.8.1-py2.py3-none-any.whl
Collecting Send2Trash (from notebook->jupyter)
  Using cached Send2Trash-1.5.0-py3-none-any.whl
Collecting widgetsnbextension~=3.1.0 (from ipywidgets->jupyter)
  Using cached widgetsnbextension-3.1.4-py2.py3-none-any.whl
Collecting prompt-toolkit<2.0.0,>=1.0.0 (from jupyter-console->jupyter)
  Using cached prompt_toolkit-1.0.15-py3-none-any.whl
Requirement already satisfied: MarkupSafe in /usr/lib/python3/dist-packages (from jinja2->nbconvert->jupyter)
Collecting jsonschema!=2.5.0,>=2.4 (from nbformat>=4.4->nbconvert->jupyter)
  Using cached jsonschema-2.6.0-py2.py3-none-any.whl
Requirement already satisfied: decorator in /usr/lib/python3/dist-packages (from traitlets>=4.2->nbconvert->jupyter)
Requirement already satisfied: six in /usr/lib/python3/dist-packages (from traitlets>=4.2->nbconvert->jupyter)
Collecting html5lib!=1.0b1,!=1.0b2,!=1.0b3,!=1.0b4,!=1.0b5,!=1.0b6,!=1.0b7,!=1.0b8,>=0.99999999pre (from bleach->nbconvert->jupyter)
  Using cached html5lib-1.0.1-py2.py3-none-any.whl
Requirement already satisfied: pexpect; sys_platform != "win32" in /usr/lib/python3/dist-packages (from ipython>=4.0.0->ipykernel->jupyter)
Requirement already satisfied: setuptools>=18.5 in /usr/lib/python3/dist-packages (from ipython>=4.0.0->ipykernel->jupyter)
Collecting jedi>=0.10 (from ipython>=4.0.0->ipykernel->jupyter)
  Using cached jedi-0.11.1-py2.py3-none-any.whl
Collecting pickleshare (from ipython>=4.0.0->ipykernel->jupyter)
  Using cached pickleshare-0.7.4-py2.py3-none-any.whl
Collecting simplegeneric>0.8 (from ipython>=4.0.0->ipykernel->jupyter)
Collecting pyzmq>=13 (from jupyter-client->ipykernel->jupyter)
  Using cached pyzmq-17.0.0-cp36-cp36m-manylinux1_x86_64.whl
Collecting python-dateutil>=2.1 (from jupyter-client->ipykernel->jupyter)
  Using cached python_dateutil-2.7.0-py2.py3-none-any.whl
Requirement already satisfied: ptyprocess; os_name != "nt" in /usr/lib/python3/dist-packages (from terminado>=0.8.1->notebook->jupyter)
Collecting wcwidth (from prompt-toolkit<2.0.0,>=1.0.0->jupyter-console->jupyter)
  Using cached wcwidth-0.1.7-py2.py3-none-any.whl
Collecting webencodings (from html5lib!=1.0b1,!=1.0b2,!=1.0b3,!=1.0b4,!=1.0b5,!=1.0b6,!=1.0b7,!=1.0b8,>=0.99999999pre->bleach->nbconvert->jupyter)
  Using cached webencodings-0.5.1-py2.py3-none-any.whl
Collecting parso==0.1.1 (from jedi>=0.10->ipython>=4.0.0->ipykernel->jupyter)
  Using cached parso-0.1.1-py2.py3-none-any.whl
Installing collected packages: ipython-genutils, traitlets, jupyter-core, jsonschema, nbformat, mistune, pandocfilters, testpath, webencodings, html5lib, bleach, pygments, entrypoints, nbconvert, tornado, parso, jedi, wcwidth, prompt-toolkit, pickleshare, simplegeneric, ipython, pyzmq, python-dateutil, jupyter-client, ipykernel, qtconsole, terminado, Send2Trash, notebook, widgetsnbextension, ipywidgets, jupyter-console, jupyter
Successfully installed Send2Trash-1.5.0 bleach-2.1.3 entrypoints-0.2.3 html5lib-1.0.1 ipykernel-4.8.2 ipython-6.2.1 ipython-genutils-0.2.0 ipywidgets-7.1.2 jedi-0.11.1 jsonschema-2.6.0 jupyter-1.0.0 jupyter-client-5.2.2 jupyter-console-5.2.0 jupyter-core-4.4.0 mistune-0.8.3 nbconvert-5.3.1 nbformat-4.4.0 notebook-5.4.0 pandocfilters-1.4.2 parso-0.1.1 pickleshare-0.7.4 prompt-toolkit-1.0.15 pygments-2.2.0 python-dateutil-2.7.0 pyzmq-17.0.0 qtconsole-4.3.1 simplegeneric-0.8.1 terminado-0.8.1 testpath-0.3.1 tornado-5.0 traitlets-4.3.2 wcwidth-0.1.7 webencodings-0.5.1 widgetsnbextension-3.1.4
~~~
kjhan@DataLX01:~/projectVirtualenv$ jupyter notebook --generate-config
~~~
Writing default config to: /home/kjhan/.jupyter/jupyter_notebook_config.py
~~~
kjhan@DataLX01:~/projectVirtualenv$ vi /home/kjhan/.jupyter/jupyter_notebook_config.py
~~~
......
## The port the notebook server will listen on.
#c.NotebookApp.port = 8888
c.NotebookApp.port = 8111
......
## The IP address the notebook server will listen on.
#c.NotebookApp.ip = 'localhost'
c.NotebookApp.ip = '192.168.1.51'
......
~~~
