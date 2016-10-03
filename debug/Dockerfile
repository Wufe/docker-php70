FROM php:7.0-fpm
MAINTAINER Simone Bembi <simone.bembi@gmail.com>

RUN docker-php-ext-install mysqli pdo pdo_mysql pcntl

COPY php-fpm.conf /usr/local/etc/php-fpm.conf
COPY www.conf /usr/local/etc/php-fpm.d/www.conf

CMD ["php"]