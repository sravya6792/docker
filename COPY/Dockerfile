


FROM almalinux

RUN dnf install nginx -y

CMD ["nginx","-g","daemon off;"]
RUN /usr/share/nginx/html/index.html
RUN +x index.html
COPY index.html  /usr/share/nginx/html/index.html

