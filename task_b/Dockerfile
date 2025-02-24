# Use official Node.js runtime as base image
FROM node:18

# Set working directory in container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json (if available)
COPY package*.json ./

# Install dependencies
RUN npm install

# Install required dependencies for the server
RUN npm install express

# Copy server.js file
COPY server.js .

# Expose port 3000
EXPOSE 3000

# Command to run the application
CMD ["node", "server.js"] 