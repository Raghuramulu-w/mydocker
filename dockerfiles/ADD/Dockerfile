FROM almalinux:8
RUN yum install nginx -y
ADD https://aws.amazon.com/docker/ /usr/share/nginx/tmp/docker.txt
ADD sample-1.tar /tmp/ 
CMD ["nginx","-g","daemon off;"]