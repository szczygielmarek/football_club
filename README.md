## Description

Football Club Application

Repositories: <br>
[API](https://github.com/szczygielmarek/football_club_api.git) - REST API - [Nest.js](https://nestjs.com/) <br>
[Panel](https://github.com/szczygielmarek/football_club_panel.git) - Administration panel - [Angular](https://angular.io/) <br>
[Frontend](https://github.com/szczygielmarek/football_club_website.git) - Website - [React](https://reactjs.org/) <br>
[App](https://github.com/szczygielmarek/football_club_app.git) - Native mobile app - [React Native](https://reactnative.dev/)

## Installation

```bash
# clone repositories
$ git clone https://github.com/szczygielmarek/football_club.git
$ cd football_club

# api
$ cd api
$ git init
$ git remote add origin https://github.com/szczygielmarek/football_club_api.git
$ git fetch origin
$ git checkout -b master --track origin/master

# panel
$ cd panel
$ git init
$ git remote add origin https://github.com/szczygielmarek/football_club_panel.git
$ git fetch origin
$ git checkout -b master --track origin/master

# website
$ cd website
$ git init
$ git remote add origin https://github.com/szczygielmarek/football_club_website.git
$ git fetch origin
$ git checkout -b master --track origin/master

# app
$ cd app
$ git init
$ git remote add origin https://github.com/szczygielmarek/football_club_app.git
$ git fetch origin
$ git checkout -b master --track origin/master
```

```bash
# build containers
$ docker-compose up --build
```

## Running the app

```bash
# run containers
$ docker-compose up

# run containers in the background
$ docker-compose up -d
```

<br>

## 

[DB] <br> 
    Host: localhost:8801 <br>
    Database: football_club <br>
    User: root <br>
    Password: admin <br><br>
[API] http://api.football_club/ <br> 
    http://localhost:8082 <br><br>
[Panel] http://admin.football_club/ <br> 
    http://localhost:8083 <br><br>
[Website] http://web.football_club/ <br> 
    http://localhost:8084 <br><br>
[Graylog] <br> 
    http://localhost:9000 <br>
    login: admin <br>
    password: admin <br> 