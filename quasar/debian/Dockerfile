FROM node:lts-slim

ENV TZ="America/Mexico_City"
RUN npm install -g npm @quasar/cli
RUN apt update -yyy && apt install -yyy git
WORKDIR /app
