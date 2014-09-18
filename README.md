[![Build Status](https://travis-ci.org/Arkilog/mysql-vagrant.svg)](https://travis-ci.org/Arkilog/mysql-vagrant)

Arkilog Ansible provisionner for MySQL on Vagrant VM 
========

Arkilog Ansible provisionner for MySQL on Vagrant VM.

Requirements
------------

An ubuntu box.

Role Variables
--------------

The are the variables and their default definition :

```YAML
arkilog_mysql_datadir: '/vagrant_data/mysql/'
arkilog_mysql_max_connections:'50'
arkilog_mysql_key_buffer_size: '32M'
arkilog_mysql_query_cache_size: '32M'
arkilog_mysql_tmp_table_size: '16M'
```

Dependencies
------------

Arkilog.mysql

License
-------

BSD

Author Information
------------------

http://www.arkilog.ma/contact
