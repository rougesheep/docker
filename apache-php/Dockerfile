# Dockerfile for building an apache/php7 install
FROM centos-base
MAINTAINER Andy Burne

# Set up repos and install stuff
RUN rpm -Uvh https://mirror.webtatic.com/yum/el6/latest.rpm
RUN yum clean all
RUN yum install -q -y httpd php70w

# Networking
EXPOSE 80
