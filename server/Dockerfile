FROM node:14-slim

WORKDIR /usr/src/app

COPY . .


RUN yarn install

EXPOSE 5000

CMD [ "index.js" ]