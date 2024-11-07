FROM nginx
EXPOSE 80
RUN rm -rf /usr/share/nginx/html && \
    rm -rf /etc/nginx/nginx.conf
COPY code /usr/share/nginx/html && \
     nginx.conf /etc/nginx/nginx.conf   
