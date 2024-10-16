FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/sravya6792/docker/blob/main/CMD/Dockerfile /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html

CMD ["nginx", "-g", "daemon off;"]
