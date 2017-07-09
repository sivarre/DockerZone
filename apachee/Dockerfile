FROM ubuntu:xenial
MAINTAINER sivva26@gmail.com
RUN apt-get update -y
RUN apt-get install apache2 -y
EXPOSE 80
ENTRYPOINT apachectl "-DFOREGROUND"

