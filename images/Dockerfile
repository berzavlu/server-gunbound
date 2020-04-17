FROM php:5.4.45-apache

LABEL maintainer="berzavlu@gmail.com"

RUN docker-php-ext-install mysql

RUN a2enmod rewrite
RUN service apache2 restart
