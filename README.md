# Py_microservises

# https://www.youtube.com/watch?v=hmkF77F9TLw&list=LL&index=1&ab_channel=freeCodeCamp.org

# venv
 python3 -m venv venv

 pip install --upgrade pip
 pip install pylint jedi
 pip install pyjwt
 pip install flask
 pip install flask_mysqldb

# MySQL
 mysql -uroot < init.sql
 (mysql -uroot -e "DROP DATABASE auth")
 (mysql -uroot -e "DROP USER auth_user@localhost")

# Docker
 docker build .
 docker tag "sha256" tmnz37/auth:tagname
 docker push tmnz37/auth:tagname