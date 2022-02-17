FROM node:14-slim

WORKDIR /usr/src/app

COPY package.json .
COPY yarn.lock .

RUN yarn install

ADD . .

EXPOSE 5000

CMD [ "index.js" ]