FROM node:14-slim

WORKDIR /usr/src/app

ADD ./package.json ./
ADD ./yarn.lock ./

RUN yarn install

ADD . .

EXPOSE 3000

CMD [ "yarn", "start" ]