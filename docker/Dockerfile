FROM nginx:latest
COPY ./docker/default.conf /etc/nginx/conf.d/default.conf
RUN apt-get update && apt-get install -y vim
EXPOSE 80
