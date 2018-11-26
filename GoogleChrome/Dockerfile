FROM centos:latest

MAINTAINER pawel.kasprowicz@outlook.com

#Installing Google Chrome

RUN echo "[google-chrome]" >> /etc/yum.repos.d/google-chrome.repo
RUN echo "name=google-chrome" >> /etc/yum.repos.d/google-chrome.repo
RUN echo "baseurl=http://dl.google.com/linux/chrome/rpm/stable/x86_64" >> /etc/yum.repos.d/google-chrome.repo
RUN echo "enabled=1" >> /etc/yum.repos.d/google-chrome.repo
RUN echo "gpgcheck=1" >> /etc/yum.repos.d/google-chrome.repo
RUN echo "gpgkey=https://dl-ssl.google.com/linux/linux_signing_key.pub" >> /etc/yum.repos.d/google-chrome.repo

RUN yum install -y google-chrome-stable
