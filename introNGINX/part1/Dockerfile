FROM nginx:latest
COPY ./html/index.html /usr/share/nginx/html/index.html
USER root
RUN apt-get update && apt-get install -y procps