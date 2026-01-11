FROM nginx:alpine

# Copy web static
COPY . /usr/share/nginx/html

# Log ra stdout/stderr cho Docker
RUN ln -sf /dev/stdout /var/log/nginx/access.log \
    && ln -sf /dev/stderr /var/log/nginx/error.log

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
