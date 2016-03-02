FROM ubuntu:15.10
MAINTAINER Brian Maher "briancmaher@gmail.com"
ENV REFRESHED_AT 2016-03-02
RUN apt-get -yqq update && apt-get -yqq install nginx
RUN mkdir -p /var/www/html/website
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
