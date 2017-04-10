FROM php:5.6-apache

MAINTAINER Rafael dos Passos Fortes <rafael.pfortes@gmail.com>

RUN docker-php-ext-install mysqli

ADD ./vhost.conf /etc/apache2/sites-enabled/