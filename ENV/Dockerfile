FROM ubuntu:16.04

#WORKDIR /usr/src/app/node

RUN apt-get update
RUN apt-get install software-properties-common -y
RUN apt-add-repository ppa:ansible/ansible
RUN apt-get update
RUN apt-get install ansible -y
RUN ansible --version
RUN lsb_release -a