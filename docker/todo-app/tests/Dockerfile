FROM mjgargani/puppeteer:trybe1.0 AS tests

WORKDIR /tests

ADD node_modules.tar.gz .

EXPOSE 3000

COPY . .

CMD ["npm", "start"]
