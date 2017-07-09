# This is a docker file based on latest Centos 7 image non privilized user entry 
FROM centos:latest 
MAINTAINER sivva26@gmail.comd

RUN useradd -ms /bin/bash user

RUN yum update -y

RUN yum install -y net-tools wget

RUN cd ~ && wget --no-check-certificate --no-cookies --header "Cookie: oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u112-b15/jdk-8u112-linux-x64.rpm"

RUN yum localinstall -y ~/jdk-8u112-linux-x64.rpm

USER user

RUN cd ~ && echo "export JAVA_HOME=/usr/java/jdk1.8.0/jdk" >> /home/ser/.bashrc
