# Versioin: 0.0.1
FROM ubuntu
LABEL tag="nginx" 
LABEL maintainer="minxiaorong@126.com"
ENV os=ubuntu
RUN apt-get update && apt-get install -y nginx \
curl \
vim

RUN echo 'Hi, I am in your container' \
>/var/www/html/index.html
EXPOSE 80