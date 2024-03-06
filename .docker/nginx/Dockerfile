FROM nginx:stable-alpine

RUN rm /etc/nginx/conf.d/default.conf

COPY configs/nginx.conf /etc/nginx/nginx.conf
COPY configs/default.conf /etc/nginx/conf.d/default.conf

CMD ["nginx", "-g", "daemon off;"]