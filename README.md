Retrieve username and date/time for all ssh, sftp, and scp logins to the
server. Display the most recent time of login. Gets all server accounts above
UID 500. Includes list from lastlogin tool.

File must be run as root in order to access /var/log/secure to log to a file.

If this has been run by root/sudo in order for a log file to be generated, then
any user can run the script to view the log. To view the log, run:

./activeusers -d

To view the info from a single user run:

./activeuser -d username

## Archived

RRCHNM archived this repository in February 2022. Last actual code activity was February 2014. If you need more information or to unarchive this repository, please contact us at  webmaster at chnm.gmu.edu
