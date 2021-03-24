FROM centos:latest
RUN yum install  openssh-server  -y
RUN yum install -y net-tools
RUN ssh-keygen -A
RUN yum install passwd -y
RUN echo redhat | passwd root --stdin
CMD /usr/sbin/sshd