#Implemnting own tomcat 
FROM ubuntu:xenial
MAINTAINER sivva26@gmail.co
RUN apt-get update -y
RUN apt-get install tomcat7 -y
ADD https://updates.jenkins-ci.org/download/war/2.68/jenkins.war /usr/local/tomcat/webapps
EXPOSE 8080
https://updates.jenkins-ci.org/download/war/2.68/jenkins.war
CMD ["catalina.sh", "run"]

