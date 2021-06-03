FROM httpd:latest
RUN apt-get -y update && apt-get install -y vim
#RUN sh /DOCKER/dockerfile/apache.sh
#RUN sed -i 's/Listen 80/Listen 8000/' /usr/local/apache2/conf/httpd.conf
#RUN sed -i 's/listen 80/listen 8000/' /etc/nginx/conf.d/default.conf

COPY httpd.conf /usr/local/apache2/conf/httpd.conf

#CMD ["httpd", "-g", "daemon off;"]
