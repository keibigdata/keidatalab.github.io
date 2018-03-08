~~~
WhoAreYou@DataLX01:~$ conda update setuptools
Solving environment: done

## Package Plan ##

  environment location: /home/WhoAreYou/anaconda3

  added / updated specs: 
    - setuptools


The following packages will be UPDATED:

    setuptools: 38.4.0-py36_0 --> 38.5.1-py36_0

Proceed ([y]/n)? y

Preparing transaction: done
Verifying transaction: done
Executing transaction: failed
ERROR conda.core.link:_execute(481): An error occurred while uninstalling package 'defaults::setuptools-38.4.0-py36_0'.
PermissionError(13, 'Permission denied')
Attempting to roll back.

Rolling back transaction: done

PermissionError(13, 'Permission denied')


WhoAreYou@DataLX01:~$ sudo conda update setuptools
[sudo] password for WhoAreYou: 
isudo: conda: command not found
WhoAreYou@DataLX01:~$ which conda
/home/WhoAreYou/anaconda3/bin/conda
WhoAreYou@DataLX01:~$ sudo /home/WhoAreYou/anaconda3/bin/conda update setuptools
Solving environment: done

## Package Plan ##

  environment location: /home/WhoAreYou/anaconda3

  added / updated specs: 
    - setuptools


The following packages will be UPDATED:

    setuptools: 38.4.0-py36_0 --> 38.5.1-py36_0

Proceed ([y]/n)? y

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
~~~
