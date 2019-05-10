# Versioin: 0.1
FROM ubuntu
LABEL tag="nginx" 
LABEL version="0.1"
LABEL role="Nginx server"
LABEL maintainer="minxiaorong@126.com"
ENV os=ubuntu
RUN apt-get update && apt-get install -y nginx \
curl \
vim
STOPSIGNAL SIGKILL
RUN echo 'Hi, I am in your container' \
>/var/www/html/index.html
EXPOSE 80

ENTRYPOINT [ "/usr/sbin/nginx" ,"-g", "daemon off;"]