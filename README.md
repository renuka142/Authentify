# A U T H E N T I F Y 


![Screenshot (41)](https://user-images.githubusercontent.com/72491412/122679091-1e4e8b00-d207-11eb-8ce8-069a257a437f.png)


## Description

A U T H E N T I F Y  is a user authentification app that lets user login and logout based on their credentials that are saved in the database when they register for the app.


## Features

- SignUp- lets user sign in . User has to pass the validation in order to sign in with their credentials
- Database- registered user gets reflected in the database
- Login- authentifies user based on their credentials
- Logout- lets user log out

## Environment Setup

- Need to download Virtual Studio Code.
  Download from [VSCode](https://code.visualstudio.com/download)
- You would need to have [Node.js](https://nodejs.org/en/) and [npm](https://www.npmjs.com/) installed.
- Install MongoDB [install](https://docs.mongodb.com/guides/server/install/)
- To enable the scope of dockerisation [install](https://www.docker.com/products/docker-desktop) Docker

## Installing Dependencies

- run `npm init -y`

- To install dependencies in this repository:<br/>
  `npm i express bcryptjs passport passport-local ejs express-ejs-layouts mongoose connect-flash express-session`

## necessary changes

- Replace <br/>`"main": "index.js" to "main": "app.js" in package.json`

## run the code

- run the code using `npm start`

## Note

If facing any difficulty in Dockerizing node.js app , then look into #1 issue.


## Live Demo

- Live Demo Of App- [A U T H E N T I F Y](https://authentify-2021.herokuapp.com/)
