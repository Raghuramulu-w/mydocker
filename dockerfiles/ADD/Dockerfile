FROM almalinux:8
RUN yum install nginx -y
ADD https://youtu.be/14CPZ3G_sGw?list=PL1jY4BuFJn1efO4Sv57kuxMBLt1ThyyUv /usr/share/nginx/tmp/
CMD ["nginx","-g","daemon off;"]