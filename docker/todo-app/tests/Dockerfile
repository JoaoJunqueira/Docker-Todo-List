FROM node:14-alpine AS tests

WORKDIR /tests

ADD node_modules.tar.gz .

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
