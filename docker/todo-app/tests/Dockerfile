FROM mjgargani/puppeteer:trybe1.0 AS build
 WORKDIR /tests
 COPY . .
 EXPOSE 3001
 ADD node_modules.tar.gz ./
 ENTRYPOINT [ "npm", "start" ]
