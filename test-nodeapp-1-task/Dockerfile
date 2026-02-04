FROM node:18-alpine

# Create app directory
WORKDIR /app

# Copy package.json 
COPY package.json ./

# Install dependencies
RUN npm install

# Copy application source code
COPY server.js ./

# Expose the application port
EXPOSE 8081

# Start the application
CMD ["npm", "start"]
