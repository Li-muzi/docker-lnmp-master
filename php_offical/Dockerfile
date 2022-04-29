FROM php:7.2-fpm

ENV TZ=Asia/Shanghai
ADD sources.list /etc/apt/sources.list
#RUN apt-get update && apt-get install -y \
#        libfreetype6-dev \
#        libjpeg62-turbo-dev \
#        libmcrypt-dev \
#        libpng12-dev \
#    && docker-php-ext-install  iconv mcrypt mysqli pdo_mysql \
#    && docker-php-ext-configure gd --with-freetype-dir=/usr/include/ --with-jpeg-dir=/usr/include/ \
#    && docker-php-ext-install  gd

ADD ./sources.list /web/
COPY ./php.ini /usr/local/etc/php/conf.d/php.ini