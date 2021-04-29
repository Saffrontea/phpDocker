FROM php:apache
COPY ./php.ini /usr/local/etc/php
RUN apt update \
  && apt install -y libfreetype6-dev libjpeg-dev libpng-dev libonig-dev \
  && docker-php-ext-install pdo_mysql mysqli mbstring gd iconv
