FROM node:lts-bullseye

USER root

RUN apt update &&\
    apt upgrade -y &&\
    apt install -y\
    zsh \
    gpg

USER node
RUN mkdir -p /home/node/workspace
WORKDIR /home/node/workspace

RUN /bin/zsh
