FROM php:7.2-fpm-alpine

RUN docker-php-ext-install pdo pdo_mysql opcache

COPY conf.d/ /usr/local/etc/php/conf.d
