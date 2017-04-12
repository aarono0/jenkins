FROM centos7:x86_64

MAINTAINER yanghaiying "haiying5@staff.sina.com.cn"

WORKDIR /home

ADD ./files/CentOS-Base.repo /etc/yum.repos.d/
RUN yum -y install epel-release
RUN yum -y install git
RUN yum -y install python-pip
RUN yum -y install

ADD ./files/vimrc /root/.vimrc
RUN mkdir /root/.pip
ADD ./files/pip.conf /root/.pip/pip.conf
