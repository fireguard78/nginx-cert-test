FROM nginx

ADD nginx.conf /etc/nginx
RUN mkdir /etc/nginx/certs
ADD server.crt /etc/nginx/certs/server.crt
ADD server.key /etc/nginx/certs/server.key
ADD client.crt /etc/nginx/certs/client.crt
RUN mkdir /etc/keys
ADD global.pass /etc/keys/global.pass
