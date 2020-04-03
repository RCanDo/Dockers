# ubuntu with addons starting bash
FROM ubuntu
MAINTAINER RCanDo <rcando@int.pl>
ENV DEBIAN_FRONTEND noninteractive
RUN apt-get update -y
RUN apt-get install mc -y
RUN apt-get clean
CMD /bin/bash -c mc 
