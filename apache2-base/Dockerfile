#docker build -t mseethar/apache-base:0.1 --rm .
FROM ubuntu:latest
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update
RUN apt-get -q -y install apache2
RUN /usr/sbin/apachectl start
RUN /usr/sbin/apachectl stop
EXPOSE 80
