FROM nginx:1.9

COPY default.templ /etc/nginx/conf.d/default.conf
COPY start-nginx.sh /start-nginx.sh
COPY nginx.conf /etc/nginx/nginx.conf

VOLUME ["/var/www/html"]

CMD ["/start-nginx.sh"]