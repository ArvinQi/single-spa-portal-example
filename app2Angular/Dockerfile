# FROM node:8-alpine as builder
# # RUN apk add --no-cache git python make openssl
# COPY . /app/
# RUN cd /app && \
#     ls -a . && \
#     npm install \
#     npm run build

FROM nginx:1-alpine
# ENV HOME="/app"
# WORKDIR ${HOME}
COPY release /usr/share/nginx/html
EXPOSE 80