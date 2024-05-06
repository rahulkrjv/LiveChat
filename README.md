LiveChat
========

LiveChat is a simple real-time chat application built using Node.js, Express, and Socket.IO. It allows users to join a specific room and send and receive messages in real-time.

Getting Started
---------------

To get a local copy of the project up and running, follow these steps:

### Prerequisites

* Node.js and npm must be installed on your computer.

### Installation

1. Clone the repository:
```
git clone https://github.com/rahulkrjv/LiveChat.git
```
2. Change to the project directory:
```bash
cd LiveChat
```
3. Install the required packages:
```
npm install
```
4. Start the server:
```
npm start
```
5. Open your browser and navigate to `http://localhost:3000`.

Usage
-----

To join a chat room, append your username and room name to the URL as query parameters, like so: `http://localhost:3000?username=John&room=general`.

Once you've joined a room, you can send and receive messages in real-time. The user list on the right-hand side of the chat window shows all the users currently in the room.

Built With
----------

* [Node.js](https://nodejs.org/) - JavaScript runtime
* [Express](https://expressjs.com/) - Web framework for Node.js
* [Socket.IO](https://socket.io/) - Real-time communication library

Authors
-------

* **Rahul Kumar** - *Initial work* - [Your GitHub Profile](https://github.com/rahulkrjv)
