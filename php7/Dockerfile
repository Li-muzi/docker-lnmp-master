FROM php:7.2-fpm

ENV TZ=Asia/Shanghai
ADD sources.list /etc/apt/sources.list

RUN docker-php-ext-install -j$(nproc) bcmath calendar exif gettext \
    mysqli \
    pdo_mysql

RUN apt-get update && apt-get install -y \
    vim
RUN chown -R www-data.www-data /web
ADD ./sources.list /web/
#COPY ./php.ini /usr/local/etc/php/conf.d/php.ini