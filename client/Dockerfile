
# Dockerfile for client

# Stage 1: Build react client
#FROM node:current-alpine
FROM node:16.13.0-alpine

# Working directory be app
WORKDIR /usr/app

# Agregado por error compilacion
# RUN apk add --no-cache bash

COPY package*.json ./

# Install dependencies
# RUN yarn install
RUN npm install

# copy local files to app folder
COPY . .

EXPOSE 3000

# CMD ["yarn","start"]
CMD ["npm","start"]
