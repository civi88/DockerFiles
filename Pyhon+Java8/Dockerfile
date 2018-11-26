FROM centos:latest

MAINTAINER pawel.kasprowicz@outlook.com

#Installing python
RUN yum install python -y
yum -y install epel-release
RUN yum install python-pip -y
RUN yum install python-virtualenv -y

#Installing Oracle JAVA8
RUN yum install wget -y
RUN wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" 
"https://download.oracle.com/otn-pub/java/jdk/8u191-b12/2787e4a523244c269598db4e85c51e0c/jre-8u191-linux-x64.rpm"
RUN yum localinstall jre-8u191-linux-x64.rpm -y
RUN wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" 
"https://download.oracle.com/otn-pub/java/jdk/8u191-b12/2787e4a523244c269598db4e85c51e0c/jdk-8u191-linux-x64.rpm"
RUN yum localinstall jdk-8u191-linux-x64.rpm -y
