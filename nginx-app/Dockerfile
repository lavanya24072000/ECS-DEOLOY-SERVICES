FROM nginx:latest

# COPY default.conf /etc/nginx/conf.d/default.conf
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80

# # Start Nginx when the container runs
CMD ["nginx", "-g", "daemon off;"]
