<h1 align="center">
  Movie Website
  <br>
</h1>

<h4 align="center">An awesome Movies websites built on top of <a href="https://nodejs.org/en/" target="_blank"> React and NodeJS </a>.</h4>

## Deployed Version
Live demo (Feel free to visit) 👉 : https://gentle-brushlands-12352.herokuapp.com/


## Key Features

* Authentication and Authorization
  - Login and logout
  - Using JWT 
* User profile
  - Update Name, email, and password
* PlayList
  - Can Make private and public PlayList


  ## Screenshots

### Front
![Front](https://github.com/Vishwkarma/MoviesWebsite/blob/main/ScreenShot/Front.png?raw=true)

### Login
![Login](https://github.com/Vishwkarma/MoviesWebsite/blob/main/ScreenShot/Signup.png?raw=true)

### Home
![Home](https://github.com/Vishwkarma/MoviesWebsite/blob/main/ScreenShot/Home.png?raw=true)

### Search Results
![Search Results](https://github.com/Vishwkarma/MoviesWebsite/blob/main/ScreenShot/Search.png?raw=true)


## Deployment
The website is deployed with git into heroku. Below are the steps taken:

git init
git add -A
git commit -m "Commit message"
heroku login
heroku create
heroku config:set CONFIG_KEY=CONFIG_VALUE
parcel build ./public/js/index.js --out-dir ./public/js --out-file bundle.js
git push heroku master
heroku open

You can also changed your website url by running this command:

heroku apps:rename natours-users



## Build With

* [NodeJS](https://nodejs.org/en/) - JS runtime environment
* [Express](http://expressjs.com/) - The web framework used
* [Mongoose](https://mongoosejs.com/) - Object Data Modelling (ODM) library
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Cloud database service
* [Heroku](https://www.heroku.com/) - Cloud platform


## Installation
You can fork the app or you can git-clone the app into your local machine. Once done that, please install all the
dependencies by running

$ npm i
set your env variables
$ npm run watch:js
$ npm run build:js
$ npm run dev (for development)
$ npm run start:prod (for production)
$ npm run debug (for debug)
$ npm start
