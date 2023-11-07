FROM node:18-alpine3.18

ENV TZ="America/Mexico_City"
RUN npm install -g npm @quasar/cli && \
 apk add git openssh-client rsync py3-pip tzdata && \
 pip install mkdocs
WORKDIR /app
