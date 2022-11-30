FROM node:16.14.0-bullseye

RUN apt update --fix-missing && \
    apt upgrade -y

RUN apt install git

WORKDIR /app