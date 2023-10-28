FROM nginx
EXPOSE 3000
EXPOSE 4000
COPY logs /var/log/nginx/logs
COPY conf/nginx.conf /etc/nginx/nginx.conf
COPY conf/proxy.conf /etc/nginx/proxy.conf
COPY conf/mime.types /etc/nginx/conf/mime.types