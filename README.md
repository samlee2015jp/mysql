# mysql

We've installed your MySQL database without a root password. To secure it run:
    ```
    mysql_secure_installation

MySQL is configured to only allow connections from localhost by default

To connect run:
    ```
    mysql -uroot

To have launchd start mysql now and restart at login:
  ```
  brew services start mysql
  
  alias mysql_start="brew services start mysql"
  alias mysql_stop="brew services stop mysql"
  alias mysql_restart="brew services restart mysql"
  ```
  
Or, if you don't want/need a background service you can just run:
  ```
  mysql.server start
  
We've installed your MySQL database without a root password. To secure it run:
    ```
    mysql_secure_installation

MySQL is configured to only allow connections from localhost by default

To connect run:
    ```
    mysql -uroot

To have launchd start mysql now and restart at login:
  ```
  brew services start mysql
Or, if you don't want/need a background service you can just run:
  ```
  mysql.server start

