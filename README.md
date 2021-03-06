# BeerSpace

![header image](/public/img/demo.png)

## Deployed app
	
Check out the app [here](https://salty-tor-49527.herokuapp.com/).

## Description

BrewSpace is a place for beer enthusiasts to track their drinks, discover new beers, and see what others are drinking.

To use the app,
- Visit the link above
- Sign up to create an account
- Sign in with your account details
- Click the "Log a beer" button to log a drink
- If the beer is not in our database, feel free to add your own custom beer, it will then be available for all users
- On your dashboard, you can see what others are drinking and visit their profiles for more info

## Technologies
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Sequelize ORM](http://docs.sequelizejs.com/)
- [Bcrypt for password hashing](https://www.npmjs.com/package/bcrypt)
- [Moment](https://momentjs.com/)
- [jQuery](https://jquery.com/)
- [Handlebars](https://handlebarsjs.com/)
- [Materialize](http://materializecss.com/)

### Installing
 
If you would like to run the application locally:
- Clone this repository to your local machine with `git clone <repo-url>`.
- Install NPM dependencies by running `npm install` in the project directory.
- Open `config/config.json` and update the development password to your local mySQL password
- Open a SQL IDE like MySQL Workbench
- Run `CREATE DATABASE movies_db;`
- Ensure that you are in the root project directory, then run `node server`.
- The application will be running at `localhost:3000/`