# server/Dockerfile
FROM node:18-alpine

# App folder
WORKDIR /app

# Dependencies install
COPY package*.json ./
RUN npm install

# Copy code
COPY . .

# Expose backend port
EXPOSE 5000

CMD ["node", "index.js"]
