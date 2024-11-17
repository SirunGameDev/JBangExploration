FROM ubuntu:latest

RUN apt update -y && apt upgrade -y
RUN apt install curl  -y
RUN curl -Ls https://sh.jbang.dev  | bash -s - app setup 

WORKDIR /ws

CMD ["/bin/sh"]