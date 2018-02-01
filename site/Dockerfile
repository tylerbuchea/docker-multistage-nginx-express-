FROM nginx
COPY ./nginx.conf /etc/nginx/conf.d/default.conf

FROM node:9.0.0
RUN rm -rf /opt/app
RUN mkdir -p /opt/app
COPY . /opt/app
WORKDIR /opt/app