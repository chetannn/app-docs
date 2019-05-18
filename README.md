## Backend
* Node.js
* Express
* MongoDB

### Dependencies used
* express - https://expressjs.com/
* mongoose - https://mongoosejs.com
* express-jwt - https://github.com/auth0/express-jwt
* lodash - https://lodash.com/
* morgan - https://www.npmjs.com/package/morgan
* cors - https://github.com/expressjs/cors
* nodemon - https://nodemon.io/
* jsonwebtoken - https://github.com/auth0/node-jsonwebtoken
* body-parser - https://www.npmjs.com/package/body-parser
* cookie-parser - https://www.npmjs.com/package/cookie-parser
* dotenv - https://www.npmjs.com/package/dotenv
* uuid - https://www.npmjs.com/package/uuid
* joi - https://www.npmjs.com/package/joi

## Frontend
* React
* Bootstrap
* Redux (optional. may be in the future)

### Dependencies used
* React.js  - https://reactjs.org/
* React Router - https://reacttraining.com/react-router/web/guides/quick-start
* Bootstrap - https://getbootstrap.com/

## API Architecture

* POST /signup -- Create a new user
* POST /signin -- Login with jwt token
* GET /signout -- Signout a user
* GET /users -- Get All Users
* GET /users/:userId -- Get a single user by userId
* PUT /user/:userId -- Update a specific user
* DELETE /user/:userId -- Delete a specific user
* POST /post/new/:userId -- create a new post for a user
* GET / -- Get All posts
* GET /posts/by/:userId -- Get All posts by user id
* PUT /post/:postId -- Update a specific post
* DELETE /post/:postId -- Delete a specific post

