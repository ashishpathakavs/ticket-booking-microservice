# Authentication Service

Authentication service built using Node.js, Express, and MongoDB. It provides user authentication functionalities, including sign-up, sign-in, sign-out, and retrieving the current user.

## Features

* User authentication with JWT
* Password is hashed
* Secure cookie-based session management
* Error handling middleware
* MongoDB as the database


## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/api/users/currentuser` | Get current logged-in user |
| POST | `/api/users/signup` | Register a new user |
| POST | `/api/users/signin` | Login user |
| POST | `/api/users/signout` | Logout user |
