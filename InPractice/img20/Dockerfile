# ubuntu with Apache
FROM ubuntu:latest
MAINTAINER RCanDo <rcando@int.pl>
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update -y
RUN apt-get install -y apache2 && apt-get clean

ENV APACHE_LOG_DIR /var/log/apache2
ENTRYPOINT /usr/sbin/apache2ctl -D FOREGROUND


