FROM node:12-alpine

ENV GULP_VERSION=2.2.0

RUN apk add --no-cache python make g++

RUN npm install --global gulp-cli@${GULP_VERSION}
RUN npm install --global @babel/register