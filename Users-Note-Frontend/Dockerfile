# Use the official Node.js image as the base image
FROM node:21.6.2

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy the local application files to the container
COPY . /usr/src/app

# Install the global command line dependency for Angular
RUN npm install -g @angular/cli

# Install the Angular application dependencies
RUN npm install

# Expose port 4200 for external access
EXPOSE 4200

# Create and run the Angular application for external access
CMD ["ng", "serve", "--host", "0.0.0.0","--disable-host-check"]    