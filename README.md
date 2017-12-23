# User-Verification

A basic user verification system where user can login and register. After registering, the user gets a username and  password, which he can use to login. Every user has a separate member's page. 

# Features 

- User can register once and select username and password.
- After registering, user can login to see personalized, member's page. 
- All the details of the user are stored in Mongo database.
- The login and logout authentication methods are a part of [passport.js](http://www.passportjs.org/)
- Passwords in Mongo database are encryted. Hashing and Salting are used for encryption.

# Install

- `Install Node.js` [Node.js](https://nodejs.org/en/)
- `Install MongoDB` [MongoDB](https://www.mongodb.com/) 

# Installing Dependencies

- `npm install express express mongojs ejs express-messages express-validator express-session connect-flash passport passport-local body-parser --save`

- `npm install bcryptjs bootstrap --save`

- `npm install nodemon -g` (Installing nodemon globally)

# Run

- `npm start` (To run globally)

- `npm run serve` (To run locally)
 