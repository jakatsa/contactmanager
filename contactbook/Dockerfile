# Use the official Node.js image with Alpine Linux
FROM node:21-alpine

# Set the working directory
WORKDIR /app

# Copy the package.json and package-lock.json (if available)
COPY package*.json ./

# Install the dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port the app runs on
EXPOSE 4173

# Run the app
CMD ["npm", "run", "preview"]
