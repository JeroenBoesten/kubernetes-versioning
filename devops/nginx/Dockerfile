FROM nginx:1.17

RUN apt-get update && apt-get -y install nano

COPY devops/nginx/default.conf /etc/nginx/conf.d/
COPY public /usr/share/nginx/html
