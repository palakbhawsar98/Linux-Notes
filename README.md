# Crontab

The crontab is a list of commands that you want to run on a regular schedule, and also the name of the command used to manage that list.

List crontab   
```
crontab -l
```
Edit crontab
```
crontab -e
```

MIN HOUR DOM MOY DOW     COMMAND
15  10   *   *   (3-5)   ech0 "$(date): checkin in." >>  /var/log/chcking

sudo less /var/spool/cron/crontab/user

ls /etc/cron.d/

crontab -e -u user

sudo vi /etc/crotab === system wide crontab
