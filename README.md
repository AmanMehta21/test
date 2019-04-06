Questions 1.

apache-playbook.yml playbook is in Quest-1 folder.

Questions 2.

Code is in Quest-2 folder.

Steps: 

1. docker build -t my-node-app Dockerfile-- to build your own name from docker file for testing
2. Based on docker version please install docker compose if it is not installed. I am using docker-compose version 2.
docker-compose build 
docker-compose up 

Access it by http://ipaddress:80


Questions 3.

Buildspec.yml is in Quest-3 folder.

Questions 4 script can be run in nohup.

nohup Admin_mongodb_apache_4.sh &

Or else we can remove sleep time and place it in cron to run every 1 minute

*/1 * * * * /path/Admin_mongodb_apache_4.sh 2> /path/error.log
