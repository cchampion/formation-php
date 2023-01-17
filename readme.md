# Docker for PHP and Apache
**ONLY for DEV, not for production**

Installing :
+ PHP 8.1.13 APACHE
+ Composer (last version)
+ Some php extentions
+ MariaDB 10.10.2
+ PHPMyAdmin 5.0.4

## Run Locally

Clone the project and go to the directory created

Run the docker compose

```shell
docker compose -p formation-php up -d
```

Log into the PHP container

```shell
docker exec -it formation-php bash
```

*MariaDB is available at port 3307*

*PHPMyAdmin is available at http://127.0.0.1:82*

*Your application will be available at http://127.0.0.1:81*
