FROM php:8.1.1-apache
LABEL org.opencontainers.image.authors="andriiabramchuk"
COPY /var/www/html/index.php /var/www/html/index.php
RUN docker-php-ext-install pdo pdo_mysql mysqli
