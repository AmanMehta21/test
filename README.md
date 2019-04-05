Questions 4 script can be run in nohup.

nohup Admin_mongodb_apache_4.sh &

Or else we can remove sleep time and place it in cron to run every 1 minute

*/1 * * * * /path/Admin_mongodb_apache_4.sh 2> /path/error.log


