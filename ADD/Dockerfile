FROM almalinux:9

RUN dnf install nginx -y

RUN rm -rf /usr/share/nginx/html/index.html

ADD https://github.com/Giribabu1492/dockerfile/blob/main/RUN/Dockerfile /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]

