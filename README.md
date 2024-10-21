==================================================
#! /bin/bash
yum install httpd -y
service httpd start
chkconfig httpd on
echo "<h1> ICICI_BANK </h1>" > /var/www/html/index.html

