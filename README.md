<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/MohamadFikryAzhar/Mockup-Web-BE">
  </a>

  <h3 align="center">Blanja : Backend E-Commerce</h3>

  <p align="center">
    Create a Node.js app for building e-commerce RESTful APIs using Express.
    <br />
    <a href="https://github.com/MohamadFikryAzhar/Mockup-Web-BE"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/MohamadFikryAzhar/Mockup-Web-BE/issues">Report Bug</a>
    ·
    <a href="https://github.com/MohamadFikryAzhar/Mockup-Web-BE/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#requirements">Requirements</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#setup-env-example">Setup .env example</a></li>
      </ul>
    </li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

Create a Node.js app for building e-commerce RESTful APIs using Express.

### Built With
This app was built with some technologies below:
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [JSON Web Tokens](https://jwt.io/)
- [Nodemailer](https://nodemailer.com/about/)
- [Socket.io](https://socket.io/)
- [Sequelize](https://sequelize.org/)
- [PostgreSQL](https://www.postgresql.org/)
- and other

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* [Node.js](https://nodejs.org/en/download/)

### Requirements
* [Node.js](https://nodejs.org/en/)
* [Postman](https://www.getpostman.com/) for testing
* [Database](./blanja.sql)

### Installation

- Clone the Repo
```
git clone https://github.com/MohamadFikryAzhar/Mockup-Web-BE.git
```
- Go To Folder Repo
```
cd Mockup-Web-BE
```
- Install Module
```
npm install
```
- Make a new database and import [blanja.sql](./blanja.sql)
- <a href="#setup-env-example">Setup .env</a>
- Type ` npm run dev` To Start Development
- Type ` npm run start` To Start Production

<p align="right">(<a href="#top">back to top</a>)</p>

### Setup .env example

Create .env file in your root project folder.

```env

# app
APP_NAME = [APP_NAME]
NODE_ENV = [NODE_ENV]
PORT = [APPLICATION_PORT]
API_URL = [BACKEND_URL]
APP_CLIENT = [FRONTEND_URL]

# database
DB_HOST = [DB_HOST]
DB_USER = [DB_USER]
DB_PASSWORD = [DB_PASSWORD]
DB_NAME = [DB_NAME]
DB_PORT = [DB_PORT]
DB_DIALECT = [DB_DIALECT]

# jwt
JWT_SECRET = [JWT_SECRET]
JWT_EXPIRED = [JWT_EXPIRED]

# google
EMAIL_FROM = [EMAIL_FROM]
EMAIL_USER = [EMAIL_USER]
GOOGLE_CLIENT_ID = [GOOGLE_CLIENT_ID]
GOOGLE_CLIENT_SECRET = [GOOGLE_CLIENT_SECRET]
REDIRECT_URI = [REDIRECT_URI]
GMAIL_REFRESH_TOKEN = [GMAIL_REFRESH_TOKEN]
DRIVE_REFRESH_TOKEN = [DRIVE_REFRESH_TOKEN]

# midtrans
MT_PRODUCTION = [MIDTRANS_PRODUCTION]
MT_CLIENT_KEY = [MIDTRANS_CLIENT_KEY]
MT_SERVER_KEY = [MIDTRANS_SERVER_KEY]
```

<p align="right">(<a href="#top">back to top</a>)</p>

## Related Project
:rocket: [`Backend Blanja`](https://github.com/MohamadFikryAzhar/Mockup-Web-BE)

:rocket: [`Frontend Blanja`](https://github.com/MohamadFikryAzhar/Mockup-Blanja-FE)
