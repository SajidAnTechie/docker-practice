FROM node:current-alpine3.15

WORKDIR /server

COPY package.json /app/package.json

RUN yarn install

COPY . /server/

CMD ["yarn","start:dev"]

