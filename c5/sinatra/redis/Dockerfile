FROM ubuntu:15.10
MAINTAINER Brian Maher "briancmaher@gmail.com"
ENV REFRESHED_AT 2016-03-02
RUN apt-get -yqq update && apt-get -yqq install redis-server redis-tools
EXPOSE 6379
ENTRYPOINT [ "/usr/bin/redis-server" ]
CMD []
