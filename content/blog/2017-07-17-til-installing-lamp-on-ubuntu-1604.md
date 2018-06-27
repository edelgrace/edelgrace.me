---
title: 'TIL: Installing LAMP on Ubuntu 16.04'
author: Edel
type: blog
date: 2017-01-01
draft: true
url: til-installing-lamp-on-ubuntu-1604
categories:
  - Life

---
**Install Apache**

    sudo apt-get update
    sudo apt-get install apache2

**Supress Syntax Warnings**

    sudo vim /etc/apache2/apache2.conf

Inside the file:

    ServerName <em>ip or domain name</em>

**Check it's okay and restart the Apache service**

    sudo apache2ctl configtest
    sudo systemctl restart apache2

**Allow traffic**

    sudo ufw allow in "Apache Full"

**Install MYSQL**

    sudo apt-get install mysql-server

**Lock down the installation**

    sudo mysql_secure_installation