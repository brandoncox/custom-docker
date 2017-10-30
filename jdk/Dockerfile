FROM centos:6.7

# Update the system
RUN yum -y update;yum clean all

RUN yum -y install java java-devel

RUN mkdir -p /app

COPY Test.java /app

CMD ["sh", "-c", "tail -f /dev/null"]
