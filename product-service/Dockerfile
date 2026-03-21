<<<<<<< HEAD
# Use Node base image
FROM node:18

# Create app directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy source code
COPY . .

# Expose port
EXPOSE 5000

# Run app
CMD ["node", "app.js"]
=======
FROM node:18

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 5000

CMD ["node", "app.js"]
>>>>>>> 7badbe0ad3ff51bf29d7f526a1f4d9ec04f0a06c
