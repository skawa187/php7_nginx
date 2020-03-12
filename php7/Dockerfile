FROM php:7.2-fpm
ARG html_dir

COPY var/www/html/ ${html_dir}
RUN sed -i 's/127.0.0.1:9000/9000/g' /usr/local/etc/php-fpm.d/www.conf

EXPOSE 9000
VOLUME ${html_dir}