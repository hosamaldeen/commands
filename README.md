
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

``sudo apt-get install curl``

``sudo curl -s https://getcomposer.org/installer | php``

``sudo mv composer.phar /usr/local/bin/composer``

``alias composer='/usr/local/bin/composer'``

**install sendmail**

``sudo apt-get install php-mail sendmail``

``nano /etc/hosts``
``127.0.0.1 localhost yourhostname``

``sudo sendmailconfig``

# Mysql 

**install phpmyadmin**
``sudo add-apt-repository universe``
``sudo apt install phpmyadmin``
``sudo phpenmod mbstring``

**enter mysql**

``mysql -p``

**create user**

``CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password';``

``GRANT ALL PRIVILEGES ON * . * TO 'newuser'@'localhost';``

**create new database**

``create database mygallery;``


**import database**

``mysql -u username -p database_name < file.sql``


