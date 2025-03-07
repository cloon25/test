FROM php:8.2-fpm-alpine

WORKDIR /var/www/html

ADD --chmod=0755 https://github.com/mlocati/docker-php-extension-installer/releases/latest/download/install-php-extensions /usr/local/bin/

RUN install-php-extensions pdo pdo_mysql gd yaml

#RUN docker-php-ext-install pdo pdo_mysql