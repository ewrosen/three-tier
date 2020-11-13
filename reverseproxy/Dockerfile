FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY ./nginx.conf /etc/nginx/conf.d/nginx.conf
COPY ./container.crt /etc/ssl/container.crt
COPY ./container.key /etc/ssl/container.key
