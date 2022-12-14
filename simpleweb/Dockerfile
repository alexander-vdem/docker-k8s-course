# Specify a base image
FROM node:current-alpine

WORKDIR /usr/app

# Install dependencies
COPY ./package.json ./
RUN npm install

COPY ./ ./

# Default command
CMD ["npm", "start"]