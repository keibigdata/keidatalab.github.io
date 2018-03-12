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
b3nn9@DataLX01:~$ sudo apt-get install python3-apt
~~~
Reading package lists... Done
Building dependency tree       
Reading state information... Done
python3-apt is already the newest version (1.1.0~beta1ubuntu0.16.04.1).
python3-apt set to manually installed.
0 upgraded, 0 newly installed, 0 to remove and 21 not upgraded.
~~~
b3nn9@DataLX01:/usr/lib/python3/dist-packages$ sudo ln -s apt_pkg.cpython-{35m,36m}-x86_64-linux-gnu.so  
b3nn9@DataLX01:/usr/lib/python3/dist-packages$ ls apt_pkg*  
~~~
apt_pkg.cpython-35m-x86_64-linux-gnu.so  apt_pkg.cpython-36m-x86_64-linux-gnu.so
~~~
sources.list change to daumkakao
~~~
b3nn9@DataLX01:~$ sudo apt-get update && sudo apt-get dist-upgrade
Hit:1 https://apt.dockerproject.org/repo ubuntu-xenial InRelease
Hit:2 http://ppa.launchpad.net/graphics-drivers/ppa/ubuntu xenial InRelease                         
Hit:3 http://ppa.launchpad.net/jonathonf/python-3.6/ubuntu xenial InRelease                         
Hit:4 http://ppa.launchpad.net/webupd8team/java/ubuntu xenial InRelease                             
Get:5 http://ftp.daumkakao.com/ubuntu xenial InRelease [247 kB]          
Get:6 http://ftp.daumkakao.com/ubuntu xenial-updates InRelease [102 kB]
Get:7 http://ftp.daumkakao.com/ubuntu xenial-backports InRelease [102 kB]
Get:8 http://ftp.daumkakao.com/ubuntu xenial-security InRelease [102 kB]
Get:9 http://ftp.daumkakao.com/ubuntu xenial/main amd64 Packages [1201 kB]
Get:10 http://ftp.daumkakao.com/ubuntu xenial/main i386 Packages [1196 kB]
Get:11 http://ftp.daumkakao.com/ubuntu xenial/main Translation-en [568 kB]
Get:12 http://ftp.daumkakao.com/ubuntu xenial/main Translation-en_GB [426 kB]
Get:13 http://ftp.daumkakao.com/ubuntu xenial/main Translation-ko [80.2 kB]
Get:14 http://ftp.daumkakao.com/ubuntu xenial/main amd64 DEP-11 Metadata [733 kB]
Get:15 http://ftp.daumkakao.com/ubuntu xenial/main DEP-11 64x64 Icons [409 kB]
Get:16 http://ftp.daumkakao.com/ubuntu xenial/restricted amd64 Packages [8344 B]
Get:17 http://ftp.daumkakao.com/ubuntu xenial/restricted i386 Packages [8684 B]
Get:18 http://ftp.daumkakao.com/ubuntu xenial/restricted Translation-en [2908 B]
Get:19 http://ftp.daumkakao.com/ubuntu xenial/restricted Translation-en_GB [2556 B]
Get:20 http://ftp.daumkakao.com/ubuntu xenial/restricted Translation-ko [716 B]
Get:21 http://ftp.daumkakao.com/ubuntu xenial/restricted amd64 DEP-11 Metadata [186 B]
Get:22 http://ftp.daumkakao.com/ubuntu xenial/universe amd64 Packages [7532 kB]
Ign:23 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  InRelease
Get:24 http://ftp.daumkakao.com/ubuntu xenial/universe i386 Packages [7512 kB]
Hit:25 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  Release
Get:27 http://ftp.daumkakao.com/ubuntu xenial/universe Translation-en [4354 kB]      
Get:28 http://ftp.daumkakao.com/ubuntu xenial/universe Translation-en_GB [3040 kB]                                  
Get:29 http://ftp.daumkakao.com/ubuntu xenial/universe Translation-ko [158 kB]                                      
Get:30 http://ftp.daumkakao.com/ubuntu xenial/universe amd64 DEP-11 Metadata [3410 kB]                              
Get:31 http://ftp.daumkakao.com/ubuntu xenial/universe DEP-11 64x64 Icons [7448 kB]                                 
Get:32 http://ftp.daumkakao.com/ubuntu xenial/multiverse amd64 Packages [144 kB]                                    
Get:33 http://ftp.daumkakao.com/ubuntu xenial/multiverse i386 Packages [140 kB]                                     
Get:34 http://ftp.daumkakao.com/ubuntu xenial/multiverse Translation-en [106 kB]                                    
Get:35 http://ftp.daumkakao.com/ubuntu xenial/multiverse Translation-en_GB [88.1 kB]                                
Get:36 http://ftp.daumkakao.com/ubuntu xenial/multiverse amd64 DEP-11 Metadata [63.8 kB]                            
Get:37 http://ftp.daumkakao.com/ubuntu xenial/multiverse DEP-11 64x64 Icons [230 kB]                                
Get:38 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 Packages [710 kB]                                  
Get:39 http://ftp.daumkakao.com/ubuntu xenial-updates/main i386 Packages [660 kB]                                   
Get:40 http://ftp.daumkakao.com/ubuntu xenial-updates/main Translation-en [295 kB]                                  
Get:41 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 DEP-11 Metadata [308 kB]                           
Get:42 http://ftp.daumkakao.com/ubuntu xenial-updates/main DEP-11 64x64 Icons [222 kB]                              
Get:43 http://ftp.daumkakao.com/ubuntu xenial-updates/restricted amd64 Packages [7560 B]                            
Get:44 http://ftp.daumkakao.com/ubuntu xenial-updates/restricted i386 Packages [7524 B]                             
Get:45 http://ftp.daumkakao.com/ubuntu xenial-updates/restricted Translation-en [2272 B]                            
Get:46 http://ftp.daumkakao.com/ubuntu xenial-updates/restricted amd64 DEP-11 Metadata [157 B]                      
Get:47 http://ftp.daumkakao.com/ubuntu xenial-updates/universe amd64 Packages [580 kB]                              
Get:48 http://ftp.daumkakao.com/ubuntu xenial-updates/universe i386 Packages [538 kB]                               
Get:49 http://ftp.daumkakao.com/ubuntu xenial-updates/universe Translation-en [234 kB]                              
Get:50 http://ftp.daumkakao.com/ubuntu xenial-updates/universe amd64 DEP-11 Metadata [190 kB]                       
Get:51 http://ftp.daumkakao.com/ubuntu xenial-updates/universe DEP-11 64x64 Icons [270 kB]                          
Get:52 http://ftp.daumkakao.com/ubuntu xenial-updates/multiverse amd64 Packages [16.2 kB]                           
Get:53 http://ftp.daumkakao.com/ubuntu xenial-updates/multiverse i386 Packages [15.3 kB]                            
Get:54 http://ftp.daumkakao.com/ubuntu xenial-updates/multiverse Translation-en [8052 B]                            
Get:55 http://ftp.daumkakao.com/ubuntu xenial-updates/multiverse amd64 DEP-11 Metadata [5888 B]                     
Get:56 http://ftp.daumkakao.com/ubuntu xenial-updates/multiverse DEP-11 64x64 Icons [14.3 kB]                       
Get:57 http://ftp.daumkakao.com/ubuntu xenial-backports/main amd64 Packages [4840 B]                                
Get:58 http://ftp.daumkakao.com/ubuntu xenial-backports/main i386 Packages [4832 B]                                 
Get:59 http://ftp.daumkakao.com/ubuntu xenial-backports/main Translation-en [3220 B]                                
Get:60 http://ftp.daumkakao.com/ubuntu xenial-backports/main amd64 DEP-11 Metadata [3324 B]                         
Get:61 http://ftp.daumkakao.com/ubuntu xenial-backports/main DEP-11 64x64 Icons [29 B]                              
Get:62 http://ftp.daumkakao.com/ubuntu xenial-backports/restricted amd64 DEP-11 Metadata [194 B]                    
Get:63 http://ftp.daumkakao.com/ubuntu xenial-backports/universe amd64 Packages [6612 B]                            
Get:64 http://ftp.daumkakao.com/ubuntu xenial-backports/universe i386 Packages [6600 B]                             
Get:65 http://ftp.daumkakao.com/ubuntu xenial-backports/universe Translation-en [3768 B]                            
Get:66 http://ftp.daumkakao.com/ubuntu xenial-backports/universe amd64 DEP-11 Metadata [4712 B]                     
Get:67 http://ftp.daumkakao.com/ubuntu xenial-backports/universe DEP-11 64x64 Icons [2716 B]                        
Get:68 http://ftp.daumkakao.com/ubuntu xenial-backports/multiverse amd64 DEP-11 Metadata [216 B]                    
Get:69 http://ftp.daumkakao.com/ubuntu xenial-backports/multiverse DEP-11 64x64 Icons [29 B]                        
Get:70 http://ftp.daumkakao.com/ubuntu xenial-security/main amd64 Packages [435 kB]                                 
Get:71 http://ftp.daumkakao.com/ubuntu xenial-security/main i386 Packages [391 kB]                                  
Get:72 http://ftp.daumkakao.com/ubuntu xenial-security/main Translation-en [189 kB]                                 
Get:73 http://ftp.daumkakao.com/ubuntu xenial-security/main amd64 DEP-11 Metadata [62.7 kB]                         
Get:74 http://ftp.daumkakao.com/ubuntu xenial-security/main DEP-11 64x64 Icons [65.1 kB]                            
Get:75 http://ftp.daumkakao.com/ubuntu xenial-security/restricted amd64 Packages [7224 B]                           
Get:76 http://ftp.daumkakao.com/ubuntu xenial-security/restricted i386 Packages [7224 B]                            
Get:77 http://ftp.daumkakao.com/ubuntu xenial-security/restricted Translation-en [2152 B]                           
Get:78 http://ftp.daumkakao.com/ubuntu xenial-security/restricted amd64 DEP-11 Metadata [200 B]                     
Get:79 http://ftp.daumkakao.com/ubuntu xenial-security/universe amd64 Packages [200 kB]                             
Get:80 http://ftp.daumkakao.com/ubuntu xenial-security/universe i386 Packages [162 kB]                              
Get:81 http://ftp.daumkakao.com/ubuntu xenial-security/universe Translation-en [102 kB]                             
Get:82 http://ftp.daumkakao.com/ubuntu xenial-security/universe amd64 DEP-11 Metadata [51.4 kB]                     
Get:83 http://ftp.daumkakao.com/ubuntu xenial-security/universe DEP-11 64x64 Icons [80.2 kB]                        
Get:84 http://ftp.daumkakao.com/ubuntu xenial-security/multiverse amd64 Packages [3208 B]                           
Get:85 http://ftp.daumkakao.com/ubuntu xenial-security/multiverse i386 Packages [3380 B]                            
Get:86 http://ftp.daumkakao.com/ubuntu xenial-security/multiverse Translation-en [1408 B]                           
Get:87 http://ftp.daumkakao.com/ubuntu xenial-security/multiverse amd64 DEP-11 Metadata [212 B]                     
Get:88 http://ftp.daumkakao.com/ubuntu xenial-security/multiverse DEP-11 64x64 Icons [29 B]                         
Fetched 45.3 MB in 9s (4854 kB/s)                                                                                   
Reading package lists... Done
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Calculating upgrade... Done
The following packages were automatically installed and are no longer required:
  cuda-9-0 cuda-command-line-tools-9-0 cuda-core-9-0 cuda-cublas-9-0 cuda-cublas-dev-9-0 cuda-cudart-9-0
  cuda-cudart-dev-9-0 cuda-cufft-9-0 cuda-cufft-dev-9-0 cuda-curand-9-0 cuda-curand-dev-9-0 cuda-cusolver-9-0
  cuda-cusolver-dev-9-0 cuda-cusparse-9-0 cuda-cusparse-dev-9-0 cuda-demo-suite-9-0 cuda-documentation-9-0
  cuda-driver-dev-9-0 cuda-libraries-9-0 cuda-libraries-dev-9-0 cuda-license-9-0 cuda-misc-headers-9-0 cuda-npp-9-0
  cuda-npp-dev-9-0 cuda-nvgraph-9-0 cuda-nvgraph-dev-9-0 cuda-nvml-dev-9-0 cuda-nvrtc-9-0 cuda-nvrtc-dev-9-0
  cuda-runtime-9-0 cuda-samples-9-0 cuda-toolkit-9-0 cuda-visual-tools-9-0 libllvm4.0
Use 'sudo apt autoremove' to remove them.
The following packages will be REMOVED:
  libcuda1-384 nvidia-384 nvidia-384-dev nvidia-opencl-icd-384
The following NEW packages will be installed:
  cuda-9-1 cuda-command-line-tools-9-1 cuda-compiler-9-1 cuda-cublas-9-1 cuda-cublas-dev-9-1 cuda-cudart-9-1
  cuda-cudart-dev-9-1 cuda-cufft-9-1 cuda-cufft-dev-9-1 cuda-cuobjdump-9-1 cuda-cupti-9-1 cuda-curand-9-1
  cuda-curand-dev-9-1 cuda-cusolver-9-1 cuda-cusolver-dev-9-1 cuda-cusparse-9-1 cuda-cusparse-dev-9-1
  cuda-demo-suite-9-1 cuda-documentation-9-1 cuda-driver-dev-9-1 cuda-gdb-9-1 cuda-gpu-library-advisor-9-1
  cuda-libraries-9-1 cuda-libraries-dev-9-1 cuda-license-9-1 cuda-memcheck-9-1 cuda-misc-headers-9-1 cuda-npp-9-1
  cuda-npp-dev-9-1 cuda-nsight-9-1 cuda-nvcc-9-1 cuda-nvdisasm-9-1 cuda-nvgraph-9-1 cuda-nvgraph-dev-9-1
  cuda-nvml-dev-9-1 cuda-nvprof-9-1 cuda-nvprune-9-1 cuda-nvrtc-9-1 cuda-nvrtc-dev-9-1 cuda-nvtx-9-1 cuda-nvvp-9-1
  cuda-runtime-9-1 cuda-samples-9-1 cuda-toolkit-9-1 cuda-tools-9-1 cuda-visual-tools-9-1 libcuda1-390
  libdrm-common libllvm5.0 nvidia-390 nvidia-390-dev nvidia-opencl-icd-390
The following packages will be upgraded:
  cuda cuda-drivers libdrm-amdgpu1 libdrm-dev libdrm-intel1 libdrm-nouveau2 libdrm-radeon1 libdrm2 libegl1-mesa
  libegl1-mesa-dev libgbm1 libgl1-mesa-dri libwayland-egl1-mesa libxatracker2 mesa-vdpau-drivers python3-gdbm
16 upgraded, 52 newly installed, 4 to remove and 0 not upgraded.
Need to get 8738 kB/1212 MB of archives.
After this operation, 2460 MB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 libegl1-mesa-dev amd64 17.2.4-0ubuntu1~16.04.4 [19.9 kB]
Get:2 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 libwayland-egl1-mesa amd64 17.2.4-0ubuntu1~16.04.4 [5874 B]
Get:3 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 libegl1-mesa amd64 17.2.4-0ubuntu1~16.04.4 [84.5 kB]
Get:4 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 libgbm1 amd64 17.2.4-0ubuntu1~16.04.4 [24.6 kB]
Get:5 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 libgl1-mesa-dri amd64 17.2.4-0ubuntu1~16.04.4 [5782 kB]
Get:6 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 libxatracker2 amd64 17.2.4-0ubuntu1~16.04.4 [1103 kB]
Get:7 http://ftp.daumkakao.com/ubuntu xenial-updates/main amd64 mesa-vdpau-drivers amd64 17.2.4-0ubuntu1~16.04.4 [1718 kB]
Fetched 8738 kB in 1s (7320 kB/s)            
Extracting templates from packages: 100%
(Reading database ... 306117 files and directories currently installed.)
Preparing to unpack .../cuda-drivers_390.30-1_amd64.deb ...
Unpacking cuda-drivers (390.30-1) over (384.81-1) ...
(Reading database ... 306116 files and directories currently installed.)
Removing nvidia-opencl-icd-384 (384.111-0ubuntu1) ...
Removing nvidia-384-dev (384.111-0ubuntu1) ...
dpkg: nvidia-384: dependency problems, but removing anyway as you requested:
 libcuda1-384 depends on nvidia-384 (>= 384.111).

Removing nvidia-384 (384.111-0ubuntu1) ...
Removing all DKMS Modules

~~~
