WhoAreYou@DataLX01:~$ cat /etc/systemd/system/jupyterhub.service
~~~
[Unit]
Description=Jupyterhub
After=syslog.target network.target

[Service]
User=root
Environment="PATH=/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/home/condadmin/anaconda3/bin"
ExecStart=/home/condadmin/anaconda3/bin/jupyterhub -f /etc/jupyterhub/jupyterhub_config.py

[Install]
WantedBy=multi-user.target
~~~  

condadmin@DataLX01:~$ which jupyterhub
/home/condadmin/anaconda3/bin/jupyterhub
condadmin@DataLX01:~$ jupyterhub --version
0.8.1

  sudo /home/condadmin/anaconda3/bin/jupyterhub --no-ssl &
