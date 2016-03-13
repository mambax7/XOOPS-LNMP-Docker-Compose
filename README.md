# XOOPS-LNMP-Docker-Compose
Setup XOOPS CMS on LNMP(Linux Nginx MySQL PHP) Server with Docker Compose
## Docker image
* php-fpm: modified by offical php docker image( 5.6)
* mysql: offical docker image (tag: latest)
* nginx: offical docker image (tag: latest)

## port settings
* php: expose 9000
* mysql: expose 3306
* nginx: ports "80:80"

## how to setup xoops
* put xoops_data and xoops_lib into this repo's ./var directory
* put htdocs into ./var/www/html

## how to add nginx configuration
* please add nginx conf file into ./conf.d directory
