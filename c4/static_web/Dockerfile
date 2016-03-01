 # Version: 0.0.1
   FROM ubuntu:15.10
   MAINTAINER Brian Maher "briancmaher@gmail.com"
   RUN apt-get update
   RUN apt-get install -y vim 
   RUN apt-get install -y nginx
   ADD index.html /var/www/html/
   ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
   EXPOSE 80
