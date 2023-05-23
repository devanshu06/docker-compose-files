FROM ubuntu:latest

LABEL maintainer="Devanshu Singh <devuvns@gmail.com>"

RUN apt-get update && apt-get install monit -y 

EXPOSE 2812

CMD ["monit", "-I", "-B", "-c", "/etc/monit/monitrc"]
