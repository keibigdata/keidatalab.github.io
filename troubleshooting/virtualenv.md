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
