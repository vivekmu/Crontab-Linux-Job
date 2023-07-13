# Crontab-Linux-Job

crontab -l

sudo apt-get update

sudo apt install cron

sudo systemctl start cron.service

sudo systemctl status cron.service

# Edit the crontab
crontab -e

#Refer corntab-e & script files to run the scheduled job

#Type crontab -e in the terminal and provide the cron scheduler (refer 25th line alone from crontab-e file)

#(i.e)  */1 * * * * /root/date-script.sh

#Give Permission

chmod u+x date-script.sh 

(or)

chmod 777 date-script.sh
