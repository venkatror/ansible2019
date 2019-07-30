https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04

1. sudo apt-get update
   package update
2. sudo apt-get install apache2
   installing apache
3. sudo systemctl restart apache2
   restarting apache2 
4. sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
   installing php 
5. sudo systemctl restart apache2
6. create a file @ /var/www/html/info.php
    <?php 
    phpinfo();
    ?>

    create home page:

    1. sudo yum update
    2. sudo yum install httpd -y
    3. sudo systemctl start httpd
    4. sudo yum install php php-mysql
    5. sudo systemctl restart httpd
     