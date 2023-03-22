FROM almalinux:latest
RUN install nginx -y
RUN ["nginx","-g","daemon off;"]
CMD [ "ping","-c5","google.com" ]
