FROM centos:7
RUN yum -y install openssh-server; yum -y install openssh-clients; systemctl start sshd; systemctl enable sshd;
RUN echo 'root:1234' | chpasswd
CMD /usr/bin/init

