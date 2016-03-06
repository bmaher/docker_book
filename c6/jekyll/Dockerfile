FROM ubuntu:trusty
MAINTAINER Brian Maher "briancmaher@gmail.com"

RUN apt-get -qq update
RUN apt-get -qq install ruby ruby-dev make nodejs
RUN gem install --no-rdoc --no-ri jekyll -v 2.5.3

VOLUME /data # source
VOLUME /var/www/html # compiled
WORKDIR /data

ENTRYPOINT [ "jekyll", "build", "--destination=/var/www/html" ]
