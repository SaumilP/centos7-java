FROM centos:7

MAINTAINER SaumilP <saumilpatel1@gmail.com>

RUN yum update -y && \
yum install -y wget && \
yum install -y java-1.8.0-openjdk-headless && \
yum clean all

# Set environment variables.
ENV HOME /root

# Define working directory.
WORKDIR /root

# Define default command.
CMD ["bash"]

