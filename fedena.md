### c9

install bundler

```
 gem install bundler
```
###[MYSQL for c9](https://c9.io/site/blog/2013/05/mysql-for-every-workspace/)

```
# start MySQL. Will create an empty database on first start

        $ mysql-ctl start
        
        # stop MySQL
        $ mysql-ctl stop
        
        # run the MySQL interactive shell
        $ mysql-ctl cli
```

Option	Value	Comment
Hostname	$IP	The same local IP as the application you run on Cloud9
Port	3306	The default MySQL port number
User	$C9_USER	Your Cloud9 user name
Password	-	No password since you can only access the DB from within the workspace
Database	c9	The database name
--------
download, copy and unzip   --change the name of folder


http://projectfedena.org/download/fedena-github

------------------------------
## database setting

database: - c9 The name of the database you want to use for fedena
username:  - c9 username Mysql username for fedena
password: - **No password** The password for the above mysql user

------
Install the rest of the gems
"gem install declarative_authorization -v 0.5.1" 
"gem install i18n -v 0.4.2" 

----
change RAILS_GEM_VERSION in /config/environment.rb

How to check ? gem list 
or
rails -v
(for ruby, ruby -v)
-----


