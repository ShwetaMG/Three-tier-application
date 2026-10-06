FROM node:24-alpine

WORKDIR /app

RUN npm install -g npm@latest

COPY package*.json ./

RUN npm install

COPY . .

CMD ["node", "index.js"]