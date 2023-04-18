FROM ubuntu:latest
RUN apt-get update
RUN apt-get install curl wget python3
RUN apt-get install awscli
RUN apt-get --purge -V remove python3
CMD tail -f /dev/null
