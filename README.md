# Overview
This project is a real-time chat application built using modern web technologies, providing a seamless communication experience. The application leverages Node.js for the server-side, React.js for the client-side, MongoDB for data storage, and Socket.io for real-time, bi-directional communication between the client and the server.

# Features
Real-Time Messaging: Instant communication with no delays.
User Authentication: Secure login and registration using JWT.
Chat Rooms: Create and join multiple chat rooms.
Private Messaging: One-on-one messaging for private conversations.
Message History: Persistent message storage using MongoDB.
Typing Indicators: Real-time typing notifications.
Online Status: User online/offline status indicators.

# Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **React.js**: A JavaScript library for building user interfaces.
- **Socket.io**: Enables real-time, bidirectional, and event-based communication.
- **MongoDB**: NoSQL database for storing chat data.
- **Mongoose**: Elegant MongoDB object modeling for Node.js.
- **JWT**: JSON Web Tokens for secure authentication.
- **Material-UI**: React components for faster and easier web development.

## Installation

```shell
git clone https://github.com/ElBanna532000/chatty-app
cd chat-app
```
Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.
