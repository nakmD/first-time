FROM node:lts-alpine

ENV LANG=C.UTF-8 \
  TZ=Asia/Tokyo

WORKDIR /app

RUN apk update && \
  apk upgrade && \
  npm install -g npm && \
  npm update -g npm && \
  npm install -g @vue/cli && \
  npm update -g @vue/cli

ENV HOST 0.0.0.0
EXPOSE 8080
