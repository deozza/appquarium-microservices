FROM nginx:latest

COPY dockered-apiGateway/apiGateway/public/ /var/www/apiGateway/public
COPY dockered-apiSpecies/apiSpecies/public/ /var/www/apiSpecies/public
COPY dockered-apiUser/apiUser/public/ /var/www/apiUser/public

COPY .docker/nginx/conf.d/ /etc/nginx/conf.d
COPY .docker/nginx/proxy.conf /etc/nginx/conf.d/default.conf