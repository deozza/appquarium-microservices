FROM nginx:latest

COPY dockered-apiGateway/apiGateway/ /var/www/apiGateway
#COPY dockered-apiSpecies/apiSpecies/ /var/www/apiSpecies
#COPY dockered-apiUser/apiUser/ /var/www/apiUser

COPY .docker/nginx/conf.d/ /etc/nginx/conf.d
#COPY .docker/nginx/default.conf /etc/nginx/conf.d/default.conf