FROM almalinux

RUN dnf install nginx -y

CMD ["nginx","-g","daemon off;"]

ENV course="aws"
RUN echo "$course"
ARG course1=devops
RUN echo "$course1"

RUN mkdir /tmp/app
WORKDIR /tmp/app
RUN echo "hi" >hello.txt
