


FROM nginx
RUN rm /etc/nginx/conf.d/default.conf

COPY /config/default.conf /etc/nginx/conf.d/
RUN cat /etc/nginx/conf.d/*.conf
Run cat /etc/nginx/nginx.conf