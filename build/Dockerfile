FROM php:7-fpm

RUN pecl install xdebug-2.6.0 \
    && docker-php-ext-enable xdebug

COPY xdebug.ini /usr/local/etc/php/conf.d/docker-php-ext-xdebug.ini