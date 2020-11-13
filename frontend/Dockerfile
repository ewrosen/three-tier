FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY ./nginx.conf /etc/nginx/conf.d/nginx.conf
COPY ./index.html /usr/share/nginx/html/index.html
COPY ./index.html /var/www/localhost/index.html
COPY ./index_fallback.html /var/www/fallback/index.html 
COPY ./.htpasswd /etc/nginx/.htpasswd
COPY ./container.crt /etc/ssl/container.crt
COPY ./container.key /etc/ssl/container.key
