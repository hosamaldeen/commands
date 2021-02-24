
# General 

**Restart Apache**
``systemctl restart apache2`` ubunto
``sudo service httpd restart`` centos

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
``apt install phpmyadmin php-mbstring php-gettext``
or
``sudo add-apt-repository universe``
``sudo apt install phpmyadmin``
then
``sudo phpenmod mbstring``

to include route to httpd.conf or apache2.conf
``nano /etc/apache2/apache2.conf`` ubunto
``nano /etc/httpd/conf/httpd.conf`` centos
add this line
``Include /etc/phpmyadmin/apache.conf``

to reconfigure it 
``sudo dpkg-reconfigure phpmyadmin``



**enter mysql**

``mysql -p``

**create user**

``CREATE USER 'newuser'@'localhost' IDENTIFIED BY 'password';``

``GRANT ALL PRIVILEGES ON * . * TO 'newuser'@'localhost';``

**create new database**

``create database mygallery;``


**import database**

``mysql -u username -p database_name < file.sql``


