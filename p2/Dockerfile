FROM ubuntu:latest
LABEL maintainer="mah713"
RUN apt-get update && apt-get install -y apache2
COPY static-website-example /var/www/html/
EXPOSE 80
CMD ["apache2ctl","-D","FOREGROUND"]

