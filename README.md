# Instructions

### Avaliable Network Container Hostnames

+ mysql
+ php
+ nginx
+ redis
+ phpmyadmin

### Installing

Run application in docker:

`docker-compose up --build`

Connecting to specific container:

`docker-compose exec (mysql|php|nginx|redis|phpmyadmin) sh`

### Access

After you successfully run docker you should be able to access to:

+ http://localhost (application in core directory)
+ http://localhost:8081 (phpmyadmin)
