FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf

COPY ./app /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off:"]
