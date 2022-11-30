FROM node:16.14.0-bullseye

RUN apt update --fix-missing && \
    apt upgrade -y

RUN mkdir /app
COPY ../first/first.txt /app

WORKDIR /app