FROM php:7.0-cli
MAINTAINER Jaehee
RUN apt-get update
RUN apt-get install -y zip unzip curl git
RUN php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');" 
RUN php composer-setup.php --install-dir=/usr/bin --filename=composer 
RUN php -r "unlink('composer-setup.php');"
