FROM node:12

# install chrome for protractor tests
RUN wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -
RUN sh -c 'echo "deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main" >> /etc/apt/sources.list.d/google.list'
RUN apt-get update && apt-get install -yq google-chrome-stable

WORKDIR /football_club/panel

# add `/app/node_modules/.bin` to $PATH
ENV PATH /football_club/panel/node_modules/.bin:$PATH

COPY package*.json ./

RUN npm install -g @angular/cli
RUN npm install

COPY . .

CMD [ "ng", "serve", "--host", "0.0.0.0"]
