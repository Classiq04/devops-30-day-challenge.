# Dockerfile
FROM nginx:alpine

# Remove the default page
RUN rm -rf /usr/share/nginx/html/*

# Copy your custom index.html to the right directory
COPY index.html /usr/share/nginx/html/

# Expose the default Nginx port
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]

