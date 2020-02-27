FROM node:12

WORKDIR /football_club/website

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "start" ]
