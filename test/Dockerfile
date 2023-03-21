FROM node:16.13.0-alpine

USER root
WORKDIR /app

COPY package*.json ./
COPY src ./src
COPY tsconfig.json ./

RUN npm install

CMD [ "npm", "start" ]
