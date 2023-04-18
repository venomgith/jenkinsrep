FROM ubuntu:latest
RUN apt-get update
RUN apt-get install curl wget python py-pip
RUN apt-get install awscli
RUN apt-get --purge -V remove py-pip
CMD tail -f /dev/null
