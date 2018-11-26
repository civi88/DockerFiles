# set the base image
FROM centos:latest

#update
RUN yum update -y

#install git

RUN yum install git -y
RUN yum install wget -y

RUN cd /root/
RUN wget https://nodejs.org/dist/v10.13.0/node-v10.13.0-linux-x64.tar.xz
RUN tar -xvf no*
RUN ls -lah
RUN echo "PATH=$PATH:/node-v10.13.0-linux-x64/bin/" > /root/.bashrc
