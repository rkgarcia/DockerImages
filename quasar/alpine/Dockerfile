FROM node:lts-alpine3.18

RUN npm install -g npm @quasar/cli && \
 apk add git openssh-client rsync py3-pip && \
 pip install mkdocs
WORKDIR /app
