# p.82
FROM ubuntu:latest
MAINTAINER RCanDo <rcando@int.pl>
ENV DEBIAN_FRONTEND noninteractive
RUN mkdir /home/root
RUN touch /home/root/file.txt
RUN echo "This is my new container with notin new." > /home/root/file.txt
RUN apt-get upadte -y
RUN apt-get install mc -y
RUN apt-get clean
CMD /bin/bash -c mc
