
FROM almalinux
RUN dnf install nginx -y
RUN mkdir /tmp/app
RUN cd /tmp/app
RUN echo "hi" >hello.txt
CMD ["nginx","-g","daemon off;"]