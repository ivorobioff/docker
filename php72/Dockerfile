FROM php:7.2.7-cli


RUN apt-get update \
    && apt-get -y install git \
    && apt-get install -y zlib1g-dev \
    && docker-php-ext-install zip \
    && curl -sS https://getcomposer.org/installer -o composer-setup.php \
    && php composer-setup.php --install-dir=/usr/local/bin --filename=composer