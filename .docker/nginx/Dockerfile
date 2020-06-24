FROM nginx:latest

COPY dockered-apiGateway/apiGateway/public/ /var/www/apiGateway/public
COPY .docker/nginx/apigateway.conf /etc/nginx/conf.d/default.conf