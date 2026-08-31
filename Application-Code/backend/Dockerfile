FROM node:14

WORKDIR /app

copy package*.json ./

RUN npm install

COPy . .

CMD ["node", "index.js"]


