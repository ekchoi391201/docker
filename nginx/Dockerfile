# Dockerfile

# Use the official Nginx image from the Docker Hub
FROM nginx:latest

# Copy custom nginx.conf to the container
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]

