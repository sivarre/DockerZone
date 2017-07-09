#This image is based upon Centos7 and ill start apache rvice in each container
FROM centos:latest
MAINTAINER sivva26@gmail.com
RUN yum update -y
RUN yum install httpd -y
#RUN systemctl enable httpd.service
#RUN systemctl restart httpd.service

RUN echo "This is a custom index file created during Image creation" > /var/www/html/index.html

ENTRYPOINT apachectl "-DFOREGROUND"
