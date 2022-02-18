FROM node:14-alpine AS build
 WORKDIR /frontend
#  COPY package*.json ./
#  RUN npm install
 COPY . .
 EXPOSE 3000
 ADD node_modules.tar.gz ./
 ENTRYPOINT [ "npm", "start" ]
