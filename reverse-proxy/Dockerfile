FROM nginx
ARG CACHEBUST=1 
COPY nginx_doiyu/nginx.conf /etc/nginx/nginx.conf
COPY certs/doiyu/cert.crt /etc/nginx/certs/cert.crt
COPY certs/doiyu/cert.key /etc/nginx/certs/cert.key