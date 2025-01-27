# JWT Project

This is a simple authentication project using Node.js, Express, MongoDB, and JWT (JSON Web Token). The project allows users to create an account, log in, and log out.

## Project Structure


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


### Files and Directories

- `app.js`: The main application file where the Express server is set up and routes are defined.
- `models/user.js`: Defines the Mongoose schema and model for the user.
- `views/index.ejs`: The EJS template for the user creation form.
- `views/login.ejs`: The EJS template for the login form.
- `public/`: Directory for static files (images, JavaScript, CSS).
- `package.json`: Contains the project metadata and dependencies.

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/jwt-project.git
   cd jwt-project


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

npm install




-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

node app.js

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
http://localhost:3000

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------


Application Logic
User Creation
Route: POST /create
Description: Creates a new user with the provided username, email, password, and age. The password is hashed using bcrypt before storing it in the database. A JWT token is generated and stored in a cookie.
View: index.ejs
User Login
Route: POST /login
Description: Authenticates a user with the provided email and password. If the credentials are correct, a JWT token is generated and stored in a cookie.
View: login.ejs
User Logout
Route: GET /logout
Description: Logs out the user by clearing the JWT token cookie and redirects to the home page.
Dependencies
express: Web framework for Node.js
mongoose: MongoDB object modeling tool
bcrypt: Library for hashing passwords
jsonwebtoken: Library for generating and verifying JWT tokens
cookie-parser: Middleware for parsing cookies
ejs: Embedded JavaScript templating
License
This project is licensed under the ISC License.





   
