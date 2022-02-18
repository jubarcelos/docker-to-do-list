FROM mjgargani/puppeteer:trybe1.0 AS build
 WORKDIR /tests
 COPY . .
 ADD node_modules.tar.gz ./
 ENTRYPOINT [ "npm", "start" ]
