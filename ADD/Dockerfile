


FROM almalinux

RUN dnf install nginx -y

CMD ["nginx","-g","daemon off;"]
RUN  rm -rf /usr/share/nginx/html/index.html

ADD https://github.com/sravya6792/docker/blob/main/CMD/Dockerfile  /usr/share/nginx/html/index.html


