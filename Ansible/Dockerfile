FROM centos:8
LABEL maintainer="rehtsira"

RUN yum update -y && yum upgrade -y && yum install vim -y && yum install python3 -y && yum install epel-release --nogpgcheck -y && yum install ansible --nogpgcheck -y && pip3 install ansible-lint