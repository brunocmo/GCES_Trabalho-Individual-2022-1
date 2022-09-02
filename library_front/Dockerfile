# syntax=docker/dockerfile:1

FROM node:18-alpine

WORKDIR /library_front

COPY package.json /library_front/

RUN npm install

COPY . /library_front/

CMD ["npm", "start"]