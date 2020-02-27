FROM node:12

WORKDIR /football_club/api

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "run", "start:dev" ]
