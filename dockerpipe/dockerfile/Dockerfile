FROM ubuntu:latest
RUN apt-get update
RUN apt-get install curl wget -y
RUN apt-get install awscli -y
RUN apt-get --purge -V remove wget -y
CMD tail -f /dev/null
