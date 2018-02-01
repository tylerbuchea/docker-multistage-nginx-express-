FROM nginx
COPY ./nginx.conf /etc/nginx/conf.d/default.conf
# EXPOSE 80
# CMD /etc/init.d/nginx restart

FROM node:9.0.0
RUN rm -rf /opt/app
RUN mkdir -p /opt/app
COPY . /opt/app
RUN cd /opt/app && npm install
WORKDIR /opt/app