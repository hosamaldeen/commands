
# General 

**Restart Apache**

``sudo service httpd restart``

``/etc/init.d/apache2 restart``


**remove folder**

``rm -rf mydir``


**zip & unzip**

``zip myzip file.zip``

``unzip myzip.zip``


**watch error log**

``tail -f /var/log/httpd/testing-error.log``


**change owner**

``sudo chown -R apache folder``


**httpd**

``cd /etc/httpd/conf``


# Installs
 
**install git**

``apt-get install git-core``

**install composer**

``curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer``

``alias composer='/usr/local/bin/composer'``


**install sendmail**

``sudo apt-get install php-mail sendmail``

``nano /etc/hosts
127.0.0.1 localhost yourhostname``

``sudo sendmailconfig``

# Mysql 

**enter mysql**

``mysql -p``


**create new database**

``create database mygallery;``


**import database**

``mysql -u username -p database_name < file.sql``


