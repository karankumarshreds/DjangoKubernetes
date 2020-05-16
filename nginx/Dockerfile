FROM nginx:alpine

EXPOSE 8001
EXPOSE 80

RUN mkdir -p /root/static/css

COPY ./my_style.css /root/static/css
COPY ./default.conf /etc/nginx/conf.d/default.conf

