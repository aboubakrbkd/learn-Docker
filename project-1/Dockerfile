# This project is about dockerizing an Apache web server
# Apache is an open source web server that provide a robust and flexible platform for serving web content
# run docker build -t project-1 . 
# then docker run -p -d 80:80 project-1 
# then go to your localhost and u will find the default page of apache2

FROM ubuntu:latest

RUN apt-get update && apt-get install -y apache2

EXPOSE 80

CMD ["apache2ctl", "-D", "FOREGROUND"]