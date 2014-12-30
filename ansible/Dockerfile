FROM ubuntu:14.04
MAINTAINER louis.gueye@gmail.com
RUN apt-get update
RUN apt-get install -y software-properties-common
RUN apt-add-repository ppa:ansible/ansible
RUN apt-get update
RUN apt-get install -y ansible
RUN rm -rf /var/lib/apt/lists/*
