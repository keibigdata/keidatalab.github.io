condadmin@DataLX01:~$ sudo pip install slackclient
~~~
The directory '/home/condadmin/.cache/pip/http' or its parent directory is not owned by the current user and the cache has been disabled. Please check the permissions and owner of that directory. If executing pip with sudo, you may want sudo's -H flag.
The directory '/home/condadmin/.cache/pip' or its parent directory is not owned by the current user and caching wheels has been disabled. check the permissions and owner of that directory. If executing pip with sudo, you may want sudo's -H flag.
Collecting slackclient
Requirement already satisfied: six<2.0a0,>=1.10 in /usr/lib/python3/dist-packages (from slackclient)
Collecting requests<3.0a0,>=2.11 (from slackclient)
  Downloading requests-2.18.4-py2.py3-none-any.whl (88kB)
    100% |████████████████████████████████| 92kB 688kB/s 
Collecting websocket-client<1.0a0,>=0.35 (from slackclient)
  Downloading websocket_client-0.47.0-py2.py3-none-any.whl (200kB)
    100% |████████████████████████████████| 204kB 1.4MB/s 
Collecting chardet<3.1.0,>=3.0.2 (from requests<3.0a0,>=2.11->slackclient)
  Downloading chardet-3.0.4-py2.py3-none-any.whl (133kB)
    100% |████████████████████████████████| 143kB 1.4MB/s 
Collecting urllib3<1.23,>=1.21.1 (from requests<3.0a0,>=2.11->slackclient)
  Downloading urllib3-1.22-py2.py3-none-any.whl (132kB)
    100% |████████████████████████████████| 133kB 1.2MB/s 
Collecting certifi>=2017.4.17 (from requests<3.0a0,>=2.11->slackclient)
  Downloading certifi-2018.1.18-py2.py3-none-any.whl (151kB)
    100% |████████████████████████████████| 153kB 1.5MB/s 
Collecting idna<2.7,>=2.5 (from requests<3.0a0,>=2.11->slackclient)
  Downloading idna-2.6-py2.py3-none-any.whl (56kB)
    100% |████████████████████████████████| 61kB 1.8MB/s 
Installing collected packages: chardet, urllib3, certifi, idna, requests, websocket-client, slackclient
  Found existing installation: chardet 2.3.0
    Uninstalling chardet-2.3.0:
      Successfully uninstalled chardet-2.3.0
  Found existing installation: urllib3 1.13.1
    Uninstalling urllib3-1.13.1:
      Successfully uninstalled urllib3-1.13.1
  Found existing installation: idna 2.0
    Uninstalling idna-2.0:
      Successfully uninstalled idna-2.0
  Found existing installation: requests 2.9.1
    Uninstalling requests-2.9.1:
      Successfully uninstalled requests-2.9.1
Successfully installed certifi-2018.1.18 chardet-3.0.4 idna-2.6 requests-2.18.4 slackclient-1.1.3 urllib3-1.22 websocket-client-0.47.0
~~~
