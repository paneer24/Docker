# Use official Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the files
COPY . .

# Expose the port Express runs on
EXPOSE 3000

# Start the server
CMD ["node", "server.js"]
