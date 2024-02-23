FROM nginx:1.16-alpine

COPY ./index.html /usr/share/nginx/html/
COPY ./assets /usr/share/nginx/html/assets
COPY ./css /usr/share/nginx/html/css
COPY ./js /usr/share/nginx/html/js
RUN ls -la  /usr/share/nginx/html