FROM lvshaco/ubuntu
MAINTAINER lvshaco
RUN apt-get update \
        && apt-get install -y nginx \
        && rm -rf /var/lib/apt/lists/* \
        && ln -sf /dev/stdout /var/log/nginx/access.log \
        && ln -sf /dev/stderr /var/log/nginx/error.log

EXPOSE 80 443
CMD ["nginx", "-g", "daemon off;"]
