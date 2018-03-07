~~~
WhoAreYou@DataLX01:~$ apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys E084DAB9
Executing: /tmp/tmp.MNRfr952mS/gpg.1.sh --keyserver
hkp://keyserver.ubuntu.com:80
--recv-keys
E084DAB9
gpg: requesting key E084DAB9 from hkp server keyserver.ubuntu.com
gpg: key E084DAB9: public key "Michael Rutter <marutter@gmail.com>" imported
gpg: Total number processed: 1
gpg:               imported: 1  (RSA: 1)
gpg: no writable keyring found: eof
gpg: error reading `[stdin]': general error
gpg: import from `[stdin]' failed: general error
gpg: Total number processed: 0
~~~
~~~
b3nn9@DataLX01:~$ sudo apt-get update
Hit:1 https://apt.dockerproject.org/repo ubuntu-xenial InRelease
Ign:2 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  InRelease                         
Hit:3 http://developer.download.nvidia.com/compute/cuda/repos/ubuntu1604/x86_64  Release                           
Hit:4 http://kr.archive.ubuntu.com/ubuntu xenial InRelease                                                         
Hit:6 http://kr.archive.ubuntu.com/ubuntu xenial-updates InRelease                                                 
Hit:7 http://ppa.launchpad.net/graphics-drivers/ppa/ubuntu xenial InRelease                                        
Hit:8 http://kr.archive.ubuntu.com/ubuntu xenial-backports InRelease                                               
Get:9 https://ftp.ussg.iu.edu/CRAN/bin/linux/ubuntu xenial/ InRelease [3590 B]                                     
Ign:9 https://ftp.ussg.iu.edu/CRAN/bin/linux/ubuntu xenial/ InRelease                                        
Hit:10 http://ppa.launchpad.net/webupd8team/java/ubuntu xenial InRelease                              
Get:11 http://security.ubuntu.com/ubuntu xenial-security InRelease [102 kB]       
Fetched 106 kB in 2s (39.8 kB/s)                      
Reading package lists... Done
W: GPG error: https://ftp.ussg.iu.edu/CRAN/bin/linux/ubuntu xenial/ InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY 51716619E084DAB9
W: The repository 'https://ftp.ussg.iu.edu/CRAN/bin/linux/ubuntu xenial/ InRelease' is not signed.
N: Data from such a repository can't be authenticated and is therefore potentially dangerous to use.
N: See apt-secure(8) manpage for repository creation and user configuration details.
b3nn9@DataLX01:~$ apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 51716619E084DAB9
Executing: /tmp/tmp.5xq4iKFzXe/gpg.1.sh --keyserver
hkp://keyserver.ubuntu.com:80
--recv-keys
51716619E084DAB9
gpg: requesting key E084DAB9 from hkp server keyserver.ubuntu.com
gpg: key E084DAB9: public key "Michael Rutter <marutter@gmail.com>" imported
gpg: Total number processed: 1
gpg:               imported: 1  (RSA: 1)
gpg: no writable keyring found: eof
gpg: error reading `[stdin]': general error
gpg: import from `[stdin]' failed: general error
gpg: Total number processed: 0
~~~
~~~
b3nn9@DataLX01:~$ apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 51716619E084DAB9
Executing: /tmp/tmp.aHRGZCznV7/gpg.1.sh --keyserver
hkp://keyserver.ubuntu.com:80
--recv-keys
51716619E084DAB9
gpg: requesting key E084DAB9 from hkp server keyserver.ubuntu.com
gpg: key E084DAB9: public key "Michael Rutter <marutter@gmail.com>" imported
gpg: Total number processed: 1
gpg:               imported: 1  (RSA: 1)
gpg: no writable keyring found: eof
gpg: error reading `[stdin]': general error
gpg: import from `[stdin]' failed: general error
gpg: Total number processed: 0
b3nn9@DataLX01:~$ apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys E084DAB9
Executing: /tmp/tmp.6T5vxyEIyY/gpg.1.sh --keyserver
hkp://keyserver.ubuntu.com:80
--recv-keys
E084DAB9
gpg: requesting key E084DAB9 from hkp server keyserver.ubuntu.com
gpg: key E084DAB9: public key "Michael Rutter <marutter@gmail.com>" imported
gpg: Total number processed: 1
gpg:               imported: 1  (RSA: 1)
gpg: no writable keyring found: eof
gpg: error reading `[stdin]': general error
gpg: import from `[stdin]' failed: general error
gpg: Total number processed: 0
~~~
