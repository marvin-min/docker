# Versioin: 0.0.1
FROM ubuntu
LABEL tag="nginx" 
LABEL maintainer="minxiaorong@126.com"
RUN apt-get update && apt-get install -y nginx \
curl
RUN echo 'Hi, I am in your container' \
>/usr/share/nginx/html/index.html
EXPOSE 80