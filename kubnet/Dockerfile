# Use an official Nginx image as the base image
FROM nginx:latest

# Copy the index.html file to the default Nginx web server path
COPY index.html /usr/share/nginx/html/
COPY index.js /usr/share/nginx/html/

# Expose port 80 to allow external access
EXPOSE 80


