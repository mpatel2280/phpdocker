FROM phpdockerio/php:8.3-fpm
WORKDIR "/application"

RUN apt-get update \
    && apt-get -y --no-install-recommends install \
        php8.3-amqp \ 
        php8.3-bcmath \ 
        php8.3-gd \ 
        php8.3-http \ 
        php8.3-mcrypt \ 
        php8.3-memcache \ 
        php8.3-memcached \ 
        php8.3-mysql \ 
        php8.3-redis \ 
        php8.3-swoole \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/* /usr/share/doc/*
