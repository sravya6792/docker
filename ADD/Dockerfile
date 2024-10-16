


FROM almalinux

RUN dnf install nginx -y

CMD ["nginx","-g","daemon off;"]
RUN  rm -rf /usr/share/nginx/html/index.html


ADD https://raw.githubusercontent.com/daws-81s/expense-infra-dev/refs/heads/main/readme.MD  /usr/share/nginx/html/index.html

RUN chmod +x  /usr/share/nginx/html/index.html
