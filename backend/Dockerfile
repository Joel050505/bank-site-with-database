FROM node:alpine
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the files
COPY . .

EXPOSE 4000

CMD ["node", "server.js"]