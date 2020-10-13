FROM httpd:2.4
RUN apt update && apt -y install iputils-ping
COPY ./public-html/ /usr/local/apache2/htdocs/