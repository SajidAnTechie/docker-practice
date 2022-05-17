FROM node:current-alpine3.15

WORKDIR /app

COPY package.json /app/package.json

RUN yarn install

COPY . /app/

CMD ["yarn","start:dev"]

