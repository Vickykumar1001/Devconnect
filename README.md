# DevConnect

Welcome to the DevConnect repository! This repository contains the source code for DevConnect, a vibrant social media platform for developers built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and Redux.

## Demo

![Screenshot](screenshot_demo.gif)

## Introduction

DevConnect is a social media platform designed for developers to connect, share knowledge, and collaborate. It encourages active participation through discussions, likes, and comments, enhancing the collective learning experience.

## Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine using:
   ```bash
   git clone https://github.com/Vickykumar1001/Devconnect.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Devconnect
   ```
3. Install dependencies using npm:

   ```bash
    npm install

   ```

4. create .env and provide correct values

.env

```js
MONGO_URI=
jwtSecret=
githubClientId=
githubSecret=
```

5. start the project

```sh
npm run server
```

- The server will be running on port 5000.

## Frontend Setup

-To start the frontend server, follow these steps:

1. Navigate to the client directory:

```bash
   cd client
```

2. Install frontend dependencies using npm:

```bash
npm install
```

3. Update the proxy in client/package.json to http://localhost:5000 to connect to the backend.

4. Start the frontend server:

```bash
npm start
```

### The frontend server will start at http://localhost:3000.
