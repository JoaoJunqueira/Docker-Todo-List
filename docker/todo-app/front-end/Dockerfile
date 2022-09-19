FROM node:14-alpine AS frontend

WORKDIR /frontend

ADD node_modules.tar.gz .

EXPOSE 3000

COPY . .

CMD ["npm", "start"]
