# Use the official Node.js image as base
FROM node:14

# Set the working directory in the container
WORKDIR /app


# Install dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose port 3000 to the outside world
EXPOSE 3000

# Command to run the application
CMD ["npm", "start"]
