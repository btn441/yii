FROM php:8.0.0-fpm-alpine
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
RUN apk add git
CMD ["php-fpm"]
WORKDIR /var/www
EXPOSE 9000
