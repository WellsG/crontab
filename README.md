# crontab

#### edit crontab
````
crontab -e
````

#### check crontab
````
crontab -l
````

#### how to debug cron job
````
sudo service rsyslog start
sudo service crond restart 
sudo tailf /var/log/cron
````

#### how to debug command, using the following command to open a new shell
````
env -i $SHELL --norc
````
