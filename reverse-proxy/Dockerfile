FROM nginx
ARG CACHEBUST=1 
COPY nginx.conf /etc/nginx/nginx.conf
COPY certs/CA_AUTH_DOIYU_MX_V2.crt /etc/nginx/certs/doiyu.crt
COPY certs/CA_AUTH_DOIYU_MX_V2-decrypted.key /etc/nginx/certs/doiyu.key