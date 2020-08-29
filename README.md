# wp-login_fail2ban_apache
filter apache log to enable a fail2ban jail and keep away bad people from your wp-login.php


1. Enable your Apache access log
https://httpd.apache.org/docs/current/logs.html

2. Copy the wp-login.conf file at your /etc/fail2ban/filter.d directory

3. Copy the wp-login.local file at your /etc/fail2ban/jail.d directory

4. You must change the "logpath" parameter

5. Restart fail2ban service
$ systemctl restart fail2ban
