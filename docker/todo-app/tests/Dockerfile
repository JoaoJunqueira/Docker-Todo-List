FROM mjgargani/puppeteer:trybe1.0 AS tests

WORKDIR /tests

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3000

CMD ["npm", "start"]
