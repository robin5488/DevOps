FROM ubuntu

COPY new.html /var/www/html/index.html

RUN apt-get update
RUN apt-get install -y nginx

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]