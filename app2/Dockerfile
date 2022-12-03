FROM node:16-alpine

WORKDIR /app

COPY package.json /app

RUN npm install

RUN npm i -g nodemon

CMD ["nodemon", "src/index.js"]
