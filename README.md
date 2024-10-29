version: '3.9'
services:
  apache:
    image: httpd:codecode
    container_name: my-apache-app
    ports:
    - '80:80'
    volumes:
    - ./website:/usr/local/apache2/htdocs