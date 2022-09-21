FROM mjgargani/puppeteer:trybe1.0 AS tests

WORKDIR /tests

ADD node_modules.tar.gz ./

COPY . .

CMD ["npm", "test"]
