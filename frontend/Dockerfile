FROM nginx
RUN rm -f /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
COPY nginx.conf /usr/share/nginx.conf
COPY code /usr/share/nginx/html/
