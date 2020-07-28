FROM php:7-fpm
LABEL maintainer="Ricardo Tribaldos <rtribaldos@barustudio.com>"

RUN echo "START----------------------------------------------------------------" \
  && mv "$PHP_INI_DIR/php.ini-development" "$PHP_INI_DIR/php.ini" \
  && apt-get update \
  && apt-get install -y libzip-dev libpng-dev \
  && docker-php-ext-install bcmath gd zip \
  && echo "-----------------------------------------------------------------END"
