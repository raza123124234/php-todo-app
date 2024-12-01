FROM php:8.1-apache
RUN apt-get update && docker-php-ext-install mysqli pdo && docker-php-ext-enable mysqli pdo

USER root  # Ensure root permissions are used for binding port 80

COPY . /var/www/html/
