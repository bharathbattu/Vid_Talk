# Video Chat Web Application

A simple, browser-based video chat platform that allows users to create and join private rooms using WebRTC technology. Designed for ease of use and privacy, the application enables seamless peer-to-peer video communication.

---

## Technologies Used

- HTML, CSS, JavaScript  
- Node.js  
- Express.js  
- WebRTC  
- Socket.IO  
- Heroku (for deployment)

---

## Project Overview

This project allows users to initiate or join real-time video calls by entering a room name and username. It uses WebRTC for establishing peer-to-peer connections and Socket.IO for signaling.

---

## How to Use

1. Visit the live app:  
   [https://vidchat-1.herokuapp.com](https://vidchat-1.herokuapp.com)

2. Enter a **Room Name** – this will act as your private session key.

3. Enter your **Username** – a name for your identity in the room.

4. Click on **Join Room** – the app will ask for camera and microphone access.

5. Share the **Room Name** with another user to join the same video call.

---

## Screenshots

### Instructions View
> Shows a step-by-step guide on how to use the application.

![Instructions View](./assets/how-to-use.png)

### Join Room Interface
> Simple UI for entering a room and joining a video call.

![Join Room UI](./assets/join-ui.png)

---

## Folder Structure

video-chat-app/
├── public/ # Static files (JS, CSS, HTML)
│ └── index.html
├── server.js # Node.js server script
├── package.json # Dependencies and scripts
├── README.md # Project documentation
└── assets/ # Screenshots
├── how-to-use.png
└── join-ui.png


---

## Deployment

The project is deployed on Heroku:  
[https://vidchat-1.herokuapp.com](https://vidchat-1.herokuapp.com)

To deploy manually:
- Ensure Node.js and npm are installed
- Run `npm install` to install dependencies
- Start the server locally with `node server.js`
- Open `http://localhost:5000` in your browser

---

## License

This project is open-source and available under the MIT License.
