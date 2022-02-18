FROM node:14-alpine AS build
 WORKDIR /app
 COPY package*.json ./
 RUN npm install
 EXPOSE 3001
 ADD node_modules.tar.gz ./
 ENTRYPOINT [ "npm", "start" ]
