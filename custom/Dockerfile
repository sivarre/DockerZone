# This docker file is used to install open-ssh-server and apache server
FROM centos:6
MAINTAINER sivva26@gmail.com
RUN yum update -y 
RUN yum -y install openssh-server openssh
RUN yum install httpd -y
#RUN service httpd start
EXPOSE 22
EXPOSE 80
ENTRYPOINT apachectl "-DFOREGROUND"
