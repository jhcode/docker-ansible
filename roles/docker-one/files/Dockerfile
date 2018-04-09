FROM ubuntu:14.04
LABEL Maintainer BABAJIDE Hassan <jide20002003@gmail.com>

RUN apt update && apt install -y openssh-server
RUN ssh-keygen -f /root/.ssh/id_rsa -t rsa -N ''
