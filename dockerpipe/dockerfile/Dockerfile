FROM ubuntu:latest
RUN apt-get update
RUN apt-get install curl wget python3 -y
RUN apt-get install awscli -y
RUN apt-get --purge -V remove python3 -y
CMD tail -f /dev/null
