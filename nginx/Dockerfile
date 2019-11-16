FROM nginx:alpine

COPY nginx.conf /etc/nginx/
COPY sites-available/default.conf /etc/nginx/sites-available/
COPY conf.d/default.conf /etc/nginx/conf.d/

CMD [ "nginx" ]

EXPOSE 80 443