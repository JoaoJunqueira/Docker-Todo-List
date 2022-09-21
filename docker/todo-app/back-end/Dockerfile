FROM node:14-alpine AS backend

WORKDIR /backend

ADD node_modules.tar.gz ./

EXPOSE 3001

COPY . .

CMD ["npm", "start"]

# https://github.com/gabrielrodriguesleite/Docker
# https://app.betrybe.com/course/back-end/docker/manipulando-imagens-no-docker/e92d2393-3508-43ab-8a67-2b2516d25864/conteudos/5a258702-f5c5-409c-b84d-20c5b9a6c600/criando-imagens-mais-robustas/c71e42c5-545d-422c-a561-07591d18df12?use_case=side_bar
