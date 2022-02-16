FROM node:14-slim

WORKDIR /usr/src/app

ADD ./package.json ./
ADD ./yarn.lock ./

RUN yarn install

ADD . .

EXPOSE 5000

CMD [ "index.js" ]