FROM node:14-alpine AS build
 WORKDIR /backend
#  COPY package*.json ./
#  RUN npm install
 COPY . .
 EXPOSE 3001
 ADD node_modules.tar.gz ./
 ENTRYPOINT [ "npm", "start" ]
