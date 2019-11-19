FROM nginx:alpine

COPY nginx.conf /etc/nginx
COPY sites-available /etc/nginx/sites-available
COPY conf.d/ /etc/nginx/conf.d

CMD [ "nginx" ]

EXPOSE 80 443
