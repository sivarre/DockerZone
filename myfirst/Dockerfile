FROM ubuntu:xenial
MAINTAINER sivva26@gmail.com
RUN apt-get update -y && apt-get install apache2 -y
RUN apt-get install tree -y
EXPOSE 80 
CMD "/bin/bash" "service apache2 start"



