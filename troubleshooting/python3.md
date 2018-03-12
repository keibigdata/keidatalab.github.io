b3nn9@DataLX01:~$ sudo add-apt-repository ppa:jonathonf/python-3.6
~~~
[sudo] password for b3nn9: 
 A plain backport of *just* Python 3.6. System extensions/Python libraries may or may not work.

Don't remove Python 3.5 from your system - it will break.
 留롮 뺣낫: https://launchpad.net/~jonathonf/+archive/ubuntu/python-3.6
怨꾩냽섎젮硫[뷀꽣] ㅻ 꾨Ⅴ쒓퀬 異붽瑜痍⑥냼섎젮硫而⑦듃濡C ㅻ 뚮윭二쇱떗쒖삤

gpg: keyring `/tmp/tmp2kmg_4l5/secring.gpg' created
gpg: keyring `/tmp/tmp2kmg_4l5/pubring.gpg' created
gpg: requesting key F06FC659 from hkp server keyserver.ubuntu.com
gpg: /tmp/tmp2kmg_4l5/trustdb.gpg: trustdb created
gpg: key F06FC659: public key "Launchpad PPA for J Fernyhough" imported
gpg: Total number processed: 1
gpg:               imported: 1  (RSA: 1)
OK
b3nn9@DataLX01:~$ echo $LANG
ko_KR.UTF-8
b3nn9@DataLX01:~$ sudo apt-get update
湲곗〈:1 https://apt.dockerproject.org/repo ubuntu-xenial InRelease
0% [kr.archive.ubuntu.com(103.22.220.133)곌껐섎뒗 以묒엯덈떎] [security.ubuntu.com(91.189.88.152)곌0% [1 InRelease gp臾댁떆:2 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  InRelease                       
0% [1 InRelease gpgv 48.7 kB] [ㅻ뜑瑜湲곕떎由щ뒗 以묒엯덈떎] [security.ubuntu.com(91.189.88.152)곌껐                 湲곗〈:3 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  Release        
0% [1 InRelease gpgv 48.7 kB] [ㅻ뜑瑜湲곕떎由щ뒗 以묒엯덈떎] [security.ubuntu.com(91.189.88.152)곌껐0% [ㅻ뜑瑜湲곕떎0% [Release.gpg gpgv 564 B] [ㅻ뜑瑜湲곕떎由щ뒗 以묒엯덈떎] [security.ubuntu.com(91.189.88.152)곌껐섎                 湲곗〈:4 http://kr.archive.ubuntu.com/ubuntu xenial InRelease                                      
0% [kr.archive.ubuntu.com(103.22.220.133)곌껐섎뒗 以묒엯덈떎] [security.ubuntu.com(91.189.88.152)곌0% [4 InRelease gp湲곗〈:6 http://kr.archive.ubuntu.com/ubuntu xenial-updates InRelease                                               
0% [kr.archive.ubuntu.com(103.22.220.133)곌껐섎뒗 以묒엯덈떎] [ㅻ뜑瑜湲곕떎由щ뒗 以묒엯덈떎] [ㅻ0% [6 InRelease gpgv 102 kB] [kr.archive.ubuntu.com(103.22.220.133)곌껐섎뒗 以묒엯덈떎] [ㅻ뜑瑜湲곕떎0% [kr.archive.ubuntu.com(103.22.220.133)곌껐섎뒗 以묒엯덈떎] [ㅻ뜑瑜湲곕떎由щ뒗 以묒엯덈떎] [ㅻ                                                          湲곗〈:7 http://kr.archive.ubuntu.com/ubuntu xenial-backports InRelease
諛쏄린:8 http://security.ubuntu.com/ubuntu xenial-security InRelease [102 kB]                                       
湲곗〈:9 http://ppa.launchpad.net/graphics-drivers/ppa/ubuntu xenial InRelease                          
諛쏄린:10 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial InRelease [18.0 kB]                           
湲곗〈:11 http://ppa.launchpad.net/webupd8team/java/ubuntu xenial InRelease                       
諛쏄린:12 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 Packages [4,492 B]
諛쏄린:13 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main i386 Packages [4,492 B]
諛쏄린:14 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main Translation-en [2,028 B]
대젮諛쏄린 131 k諛붿씠 뚯슂쒓컙 3珥(33.3 k諛붿씠珥

⑦궎吏 紐⑸줉쎈뒗 以묒엯덈떎... 꾨즺
b3nn9@DataLX01:~$ export LANG=0
b3nn9@DataLX01:~$ sudo apt-get update
Hit:1 https://apt.dockerproject.org/repo ubuntu-xenial InRelease
Ign:2 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  InRelease                          
Hit:3 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  Release                            
Hit:4 http://kr.archive.ubuntu.com/ubuntu xenial InRelease                                                          
Hit:6 http://kr.archive.ubuntu.com/ubuntu xenial-updates InRelease                                                  
Get:7 http://security.ubuntu.com/ubuntu xenial-security InRelease [102 kB]                                          
Hit:8 http://kr.archive.ubuntu.com/ubuntu xenial-backports InRelease                                                
Hit:9 http://ppa.launchpad.net/graphics-drivers/ppa/ubuntu xenial InRelease                                   
Hit:10 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial InRelease  
Hit:11 http://ppa.launchpad.net/webupd8team/java/ubuntu xenial InRelease       
Fetched 102 kB in 2s (36.5 kB/s)
Reading package lists... Done
b3nn9@DataLX01:~$ sudo apt-get install python3.6
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  libpython3.6-minimal libpython3.6-stdlib python3.6-minimal
Suggested packages:
  python3.6-venv python3.6-doc binfmt-support
The following NEW packages will be installed:
  libpython3.6-minimal libpython3.6-stdlib python3.6 python3.6-minimal
0 upgraded, 4 newly installed, 0 to remove and 21 not upgraded.
Need to get 4361 kB of archives.
After this operation, 23.7 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 libpython3.6-minimal amd64 3.6.3-1ubuntu1~16.04.york1 [572 kB]
Get:2 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 python3.6-minimal amd64 3.6.3-1ubuntu1~16.04.york1 [1451 kB]
Get:3 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 libpython3.6-stdlib amd64 3.6.3-1ubuntu1~16.04.york1 [2122 kB]
Get:4 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 python3.6 amd64 3.6.3-1ubuntu1~16.04.york1 [217 kB]
Fetched 4361 kB in 44s (99.0 kB/s)                                                                                  
perl: warning: Setting locale failed.
perl: warning: Please check that your locale settings:
        LANGUAGE = "ko_KR:ko:en_GB:en",
        LC_ALL = (unset),
        LANG = "0"
    are supported and installed on your system.
perl: warning: Falling back to the standard locale ("C").
locale: Cannot set LC_CTYPE to default locale: No such file or directory
locale: Cannot set LC_MESSAGES to default locale: No such file or directory
locale: Cannot set LC_ALL to default locale: No such file or directory
Selecting previously unselected package libpython3.6-minimal:amd64.
(Reading database ... 305103 files and directories currently installed.)
Preparing to unpack .../libpython3.6-minimal_3.6.3-1ubuntu1~16.04.york1_amd64.deb ...
Unpacking libpython3.6-minimal:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Selecting previously unselected package python3.6-minimal.
Preparing to unpack .../python3.6-minimal_3.6.3-1ubuntu1~16.04.york1_amd64.deb ...
Unpacking python3.6-minimal (3.6.3-1ubuntu1~16.04.york1) ...
Selecting previously unselected package libpython3.6-stdlib:amd64.
Preparing to unpack .../libpython3.6-stdlib_3.6.3-1ubuntu1~16.04.york1_amd64.deb ...
Unpacking libpython3.6-stdlib:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Selecting previously unselected package python3.6.
Preparing to unpack .../python3.6_3.6.3-1ubuntu1~16.04.york1_amd64.deb ...
Unpacking python3.6 (3.6.3-1ubuntu1~16.04.york1) ...
Processing triggers for man-db (2.7.5-1) ...
Processing triggers for bamfdaemon (0.5.3~bzr0+16.04.20180209-0ubuntu1) ...
Rebuilding /usr/share/applications/bamf-2.index...
Processing triggers for desktop-file-utils (0.22-1ubuntu5.1) ...
Processing triggers for gnome-menus (3.13.3-6ubuntu3.1) ...
Processing triggers for mime-support (3.59ubuntu1) ...
Setting up libpython3.6-minimal:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Setting up python3.6-minimal (3.6.3-1ubuntu1~16.04.york1) ...
Setting up libpython3.6-stdlib:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Setting up python3.6 (3.6.3-1ubuntu1~16.04.york1) ...
b3nn9@DataLX01:~$ 
~~~



b3nn9@DataLX01:~$ sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.5 1
~~~
update-alternatives: using /usr/bin/python3.5 to provide /usr/bin/python3 (python3) in auto mode
~~~
b3nn9@DataLX01:~$ sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 2
~~~
update-alternatives: using /usr/bin/python3.6 to provide /usr/bin/python3 (python3) in auto mode
~~~
b3nn9@DataLX01:~$ sudo update-alternatives --config python3
~~~
There are 2 choices for the alternative python3 (providing /usr/bin/python3).

  Selection    Path                Priority   Status
------------------------------------------------------------
* 0            /usr/bin/python3.6   2         auto mode
  1            /usr/bin/python3.5   1         manual mode
  2            /usr/bin/python3.6   2         manual mode

Press <enter> to keep the current choice[*], or type selection number:
~~~
b3nn9@DataLX01:~$ sudo apt-get install python-dev
~~~
Reading package lists... Done
Building dependency tree       
Reading state information... Done
python-dev is already the newest version (2.7.12-1~16.04).
0 upgraded, 0 newly installed, 0 to remove and 21 not upgraded.
b3nn9@DataLX01:~$ sudo apt-get install python3-dev
Reading package lists... Done
Building dependency tree       
Reading state information... Done
python3-dev is already the newest version (3.5.1-3).
0 upgraded, 0 newly installed, 0 to remove and 21 not upgraded.
b3nn9@DataLX01:~$ /usr/bin/pip3 --version^C
b3nn9@DataLX01:~$ sudo apt-get install python3.6-dev
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  libpython3.6 libpython3.6-dev
The following NEW packages will be installed:
  libpython3.6 libpython3.6-dev python3.6-dev
0 upgraded, 3 newly installed, 0 to remove and 21 not upgraded.
Need to get 4415 kB of archives.
After this operation, 21.0 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 libpython3.6 amd64 3.6.3-1ubuntu1~16.04.york1 [1433 kB]
Get:2 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 libpython3.6-dev amd64 3.6.3-1ubuntu1~16.04.york1 [2462 kB]
Get:3 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial/main amd64 python3.6-dev amd64 3.6.3-1ubuntu1~16.04.york1 [520 kB]
Fetched 4415 kB in 50s (86.9 kB/s)                                                                                  
perl: warning: Setting locale failed.
perl: warning: Please check that your locale settings:
        LANGUAGE = "ko_KR:ko:en_GB:en",
        LC_ALL = (unset),
        LANG = "0"
    are supported and installed on your system.
perl: warning: Falling back to the standard locale ("C").
locale: Cannot set LC_CTYPE to default locale: No such file or directory
locale: Cannot set LC_MESSAGES to default locale: No such file or directory
locale: Cannot set LC_ALL to default locale: No such file or directory
Selecting previously unselected package libpython3.6:amd64.
(Reading database ... 305945 files and directories currently installed.)
Preparing to unpack .../libpython3.6_3.6.3-1ubuntu1~16.04.york1_amd64.deb ...
Unpacking libpython3.6:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Selecting previously unselected package libpython3.6-dev:amd64.
Preparing to unpack .../libpython3.6-dev_3.6.3-1ubuntu1~16.04.york1_amd64.deb ...
Unpacking libpython3.6-dev:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Selecting previously unselected package python3.6-dev.
Preparing to unpack .../python3.6-dev_3.6.3-1ubuntu1~16.04.york1_amd64.deb ...
Unpacking python3.6-dev (3.6.3-1ubuntu1~16.04.york1) ...
Processing triggers for libc-bin (2.23-0ubuntu10) ...
Processing triggers for man-db (2.7.5-1) ...
Setting up libpython3.6:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Setting up libpython3.6-dev:amd64 (3.6.3-1ubuntu1~16.04.york1) ...
Setting up python3.6-dev (3.6.3-1ubuntu1~16.04.york1) ...
Processing triggers for libc-bin (2.23-0ubuntu10) ...
~~~
b3nn9@DataLX01:~$ sudo apt-get install python-apt
~~~
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Suggested packages:
  python-apt-dbg python-apt-doc
The following NEW packages will be installed:
  python-apt
0 upgraded, 1 newly installed, 0 to remove and 21 not upgraded.
Need to get 139 kB of archives.
After this operation, 632 kB of additional disk space will be used.
Get:1 http://kr.archive.ubuntu.com/ubuntu xenial-updates/main amd64 python-apt amd64 1.1.0~beta1ubuntu0.16.04.1 [139 kB]
Fetched 139 kB in 3s (43.0 kB/s)     
perl: warning: Setting locale failed.
perl: warning: Please check that your locale settings:
        LANGUAGE = "ko_KR:ko:en_GB:en",
        LC_ALL = (unset),
        LANG = "0"
    are supported and installed on your system.
perl: warning: Falling back to the standard locale ("C").
locale: Cannot set LC_CTYPE to default locale: No such file or directory
locale: Cannot set LC_MESSAGES to default locale: No such file or directory
locale: Cannot set LC_ALL to default locale: No such file or directory
Selecting previously unselected package python-apt.
(Reading database ... 306089 files and directories currently installed.)
Preparing to unpack .../python-apt_1.1.0~beta1ubuntu0.16.04.1_amd64.deb ...
Unpacking python-apt (1.1.0~beta1ubuntu0.16.04.1) ...
Setting up python-apt (1.1.0~beta1ubuntu0.16.04.1) ...
~~~
