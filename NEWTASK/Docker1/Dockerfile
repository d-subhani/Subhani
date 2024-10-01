FROM ubuntu:latest
WORKDIR /app
RUN apt-get update && apt-get install -y apache2
EXPOSE 80
CMD [ "apchetl", "-D", "FOREGROUND" ]