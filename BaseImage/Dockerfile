FROM fedora:latest
MAINTAINER grantseltzer@gmail.com
RUN mkdir /root/assignment
RUN dnf install -y make gcc
RUN dnf clean all
WORKDIR /root/assignment
ADD Installed.txt /root/assignment/Installed.txt
