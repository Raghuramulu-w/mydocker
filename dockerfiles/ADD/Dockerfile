FROM almalinux:8
RUN yum install nginx -y
ADD https://aws.amazon.com/docker/ /usr/share/nginx/tmp/docker.txt
CMD ["nginx","-g","daemon off;"]