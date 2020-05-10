


FROM nginx
RUN rm /etc/nginx/conf.d/default.conf

COPY /config/default.conf /etc/nginx/conf.d/
RUN cat /etc/nginx/conf.d/*.conf
Run cat /etc/nginx/nginx.conf
RUN add-apt-repository ppa:certbot/certbot
RUN apt-get update
RUN apt-get install python-certbot-nginx