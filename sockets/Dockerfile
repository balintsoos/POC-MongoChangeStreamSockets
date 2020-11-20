FROM node:15.0.1-alpine

WORKDIR /project

COPY ./src/package*.json ./

RUN npm ci

COPY ./src ./

CMD sleep 5 && npm start
