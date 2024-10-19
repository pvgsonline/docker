FROM almalinux:9
RUN dnf install nginx -y
RUN rm /usr/share/nginx/html/index.html
RUN echo "<h1>this is my nginx page</h1>" > index.html
COPY index.html /usr/share/nginx/html/
CMD ["niginx" , "-g" , "daemon off;"]