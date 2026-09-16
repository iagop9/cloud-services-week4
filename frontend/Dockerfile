FROM nginxinc/nginx-unprivileged:alpine

COPY frontend/nginx.conf /etc/nginx/nginx.conf
COPY frontend/index.html /usr/share/nginx/html/index.html

EXPOSE 8080
