# Amazon Lightsail
# ubuntu18.04 LTS

-------------------------------------------------------------------

# HallowinGhost

-------------------------------------------------------------------
sudo su

apt-get update

apt-get install apache2

[y]

[yes]

------------------------------------------------------------------
apt update

apt install -y php

------------------------------------------------------------------
apt-get install mysql-server mysql-client

[y]

-------------------------------------------------------------------
mysql -u root -p

[ ]

-------------------------------------------------------------------
-------------------------------------------------------------------
use mysql;  

update mysql.user set authentication_string=password('[password]') where user='root' and Host ='localhost';

-------------------------------------------------------------------
update user set  plugin="mysql_native_password";

flush privileges;

quit;

mysql -u root -p

[password]

--------------------------------------------------------------------

create database mail_pass;

exit;

-------------------------------------------------------------------
cd /var/www/

rm -rf html

mkdir html

cd html/

git clone https://github.com/TsugawaNaoki0/organized_homepage.git

git clone https://github.com/TsugawaNaoki0/login_database.git

git clone https://github.com/TsugawaNaoki0/search.git

git clone https://github.com/TsugawaNaoki0/zero_wiki.git

mv ./login_database/* ./

git clone https://github.com/TsugawaNaoki0/zero_wiki.git

chmod 777 zero_wiki/data/*

cd zero_wiki

while true; do python3 zeroWiki.py; sleep 60s; done

-------------------------------------------------------------------

apt install php-pdo

yes | apt install php-mysql

sudo a2enmod proxy_fcgi setenvif

sudo apt install libapache2-mod-php libapache2-mod-php

sudo service apache2 restart

-------------------------------------------------------------------

yes | apt install python3-numpy

yes | apt install python3-matplotlib

yes | apt install python3-pip

pip3 install beautifulsoup4

apt-get install language-pack-ja-base language-pack-ja

locale-gen ja_JP.UTF-8

echo export LANG=ja_JP.UTF-8 >> ~/.profile

source ~/.profile

pip3 install qrcode

apt install mysql-server

apt install php-pdo

--------------------------------------------------------------------
/organized_homepage/registration/new_comer.html

--------------------------------------------------------------------
--------------------------------------------------------------------
--------------------------------------------------------------------
--------------------------------------------------------------------
--------------------------------------------------------------------
[Apache]
Server version: Apache/2.4.29 (Ubuntu)

Server built:   2022-03-16T16:53:42


[PHP]
PHP 7.2.24-0ubuntu0.18.04.11 (cli) (built: Mar  2 2022 17:52:35) ( NTS )

Copyright (c) 1997-2018 The PHP Group

Zend Engine v3.2.0, Copyright (c) 1998-2018 Zend Technologies
    
with Zend OPcache v7.2.24-0ubuntu0.18.04.11, Copyright (c) 1999-2018, by Zend Technologies


[MySQL]

mysql  Ver 14.14 Distrib 5.7.38, for Linux (x86_64) using  EditLine wrapper
