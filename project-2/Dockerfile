FROM ubuntu:latest

RUN apt-get update && apt-get upgrade -y \
	&& apt-get install -y nginx

COPY /src /var/www/html

EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]