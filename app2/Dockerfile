FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hello, I am from APP-2" > /ur/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]