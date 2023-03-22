FROM almalinux:latest
RUN  yum install nginx -y
RUN ["nginx","-g","daemon off;"]
CMD [ "ping","-c5","google.com" ]
