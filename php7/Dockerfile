FROM php:7.2-fpm

ENV TZ=Asia/Shanghai
ADD sources.list /etc/apt/sources.list
ADD ./sources.list /web/
#ADD /home/code/offical.com /var/www/offical.com
RUN docker-php-ext-install -j$(nproc) bcmath calendar exif gettext \
    mysqli \
    pdo_mysql

RUN apt-get update && apt-get install -y \
    vim \
    procps
RUN chown -R www-data.www-data /var/www
COPY ./php.ini /usr/local/etc/php/conf.d/php.ini