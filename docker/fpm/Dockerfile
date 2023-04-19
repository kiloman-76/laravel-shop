FROM php:8.1.0-alpine

RUN apk update && \
    apk add --no-cache \
    curl \
    libzip-dev

RUN docker-php-ext-install pdo_mysql zip

WORKDIR /var/www
