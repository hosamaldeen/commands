#restart apache
sudo service httpd restart
/etc/init.d/apache2 restart

#remove folder
rm -rf mydir

#install git 
yum install git

#install composer
curl -sS https://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
alias composer='/usr/local/bin/composer'

#zip & unzip
zip myzip file.zip
unzip myzip.zip

#watch error log
tail -f /var/log/httpd/testing-error.log

#import database
mysql -u username -p database_name < file.sql

#change owner 
sudo chown -R apache folder

#httpd
cd /etc/httpd/conf

** install sendmail**
sudo apt-get install php-mail sendmail

nano /etc/hosts
127.0.0.1 localhost yourhostname

sudo sendmailconfig

/////////////////////
##mysql 

#enter mysql 
mysql -p

#create new database
create database mygallery;

#import file 
mysql -u USERNAME -p DATABASE < backup.sql



