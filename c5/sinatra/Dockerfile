FROM ubuntu:15.10
MAINTAINER Brian Maher "briancmaher@gmail.com"
ENV REFRESHED_AT 2016-03-02

RUN apt-get update -yqq && apt-get -yqq install ruby ruby-dev build-essential redis-tools
RUN gem install --no-rdoc --no-ri sinatra json redis

RUN mkdir -p /opt/webapp

EXPOSE 4567

CMD [ "/opt/webapp/bin/webapp" ]
