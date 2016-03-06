FROM brianmaher/redis
MAINTAINER Brian Maher "briancmaher@gmail.com"

ENTRYPOINT [ "redis-server", "--logfile /var/log/redis/redis-replica.log", "--slaveof redis_primary 6379" ]
