FROM node:14-slim

WORKDIR /usr/src/app

COPY package.json .
COPY yarn.lock .

RUN yarn install

ADD . .

EXPOSE 3000

CMD [ "yarn", "start" ]