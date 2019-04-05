#!/bin/bash
# Hardcode value can be passed from command line and same can be used as parameters
while true
do 
service="apache2"
email="Nikhil.singh@appinventiv.com"
from="server.monitor@example.com"
host=`hostname`
if (( $(ps -ef | grep -v grep | grep $service | wc -l) > 0 ))
then
echo "$service is running"
else
/etc/init.d/$service start
if (( $(ps -ef | grep -v grep | grep $service | wc -l) > 0 ))
then
subject=”$service at $host has been started”
echo -e "$service at $host wasn’t running and has been started" | mailx -a  -s "$subject" -r "$from" -c "$email"
else
subject=”$service at $host is not running”
echo -e "$service at $host is stopped and cannot be started!!!" | mailx -a  -s "$subject" -r "$from" -c "$email"
fi
fi
    sleep 60
done

#!/bin/bash
while true
do 
service="mongod"
email="Nikhil.singh@appinventiv.com"
from="server.monitor@example.com"
host=`hostname`
if (( $(ps -ef | grep -v grep | grep $service | wc -l) > 0 ))
then
echo "$service is running"
else
/etc/init.d/$service start
if (( $(ps -ef | grep -v grep | grep $service | wc -l) > 0 ))
then
subject=”$service at $host has been started”
echo -e "$service at $host wasn’t running and has been started" | mailx -a  -s "$subject" -r "$from" -c "$email"
else
subject=”$service at $host is not running”
echo -e "$service at $host is stopped and cannot be started!!!" | mailx -a  -s "$subject" -r "$from" -c "$email"
fi
fi
    sleep 60
done
