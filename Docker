# Use the official NGINX image as base
FROM nginx:latest

# Copy index.html into the default NGINX html directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80
EXPOSE 80

# Start NGINX
CMD ["nginx", "-g", "daemon off;"]
