# Text-A-Lot

> A Realtime Group Chat Application

A simple realtime chat apoplication made using MERN-Stack[React JS+ Node JS + MongoDB]


### Few Screenshots

![Homepage](/screenshots/1.png "Homepage")
![Chatpage](/screenshots/2.png "Chatpage")
![Groupchat](/screenshots/3.png "Groupchat")

## Features

- Latest features of JavaScript i.e. ES6, ES7, ES8 is used
- [React JS Hooks](https://reactjs.org/docs/hooks-intro.html) are used with Functional components
- ES8 `async/await` is used

<br/>

<ul>
 <li> This is Simple Chat Application </li>
 <li> It is a Full Stack Application </li>
</ul>

- All the user details, group chats and conversations are stored in the [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).

<ul>
 <li>Login/Signup as well as Logout feature is added </li>
 <li>Guest User Login added</li>
 <li>Error will be shown if the credentials are not correct</li>
</ul>

- Real time communication & notification is supported using <a href="https://www.npmjs.com/package/socket.io">Socket.io</a>

<ul>
 <li> Realtime One on One chats and group chats </li>
 <li> Functionality and features like Search for chats, create a group, add or remove partricipants. </li>   
 <li> typing... animation. </li>
 <li> Online / Offline status are shown . </li>
 <li> Read / Unread status of conversation is supported
 <li> All the conversation are stored in the database i.e. <i>persistant</i>
</ul>


## Tech Stack

MongoDB, Express, React, Node, Socket.IO, Chakra-UI


## Usage

**Test users**

| Email | Password  |
| -------- | --------- |

``` Or Use the guest user login feature.  ```


### Env Variables

Create a .env file in the root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = <yourMongoDbUri>
JWT_SECRET = <yourSecret>
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run
Run frontend (:3000) & backend (:5000)
```
# Run frontend only
cd frontend
npm start 

# Run backend only
npm start
```

## Build & Deploy

```
# Create frontend production build
cd frontend
npm run build
```
