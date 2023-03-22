FROM alamlinux
RUN install inginx -y
RUN ["nginx","-g","daemon off;"]
CMD [ "ping","-c5","google.com" ]
