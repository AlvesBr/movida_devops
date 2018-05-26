FROM debian:jessie
MAINTAINER BRUNO ALVES br.alves7@gmail.com

RUN apt-get update && apt-get install -y nginx && apt-get clean

RUN usermod -u 1000 www-data
CMD ["nginx"]

EXPOSE 80
EXPOSE 443
