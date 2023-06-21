# Chirpy-Chat

A real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) and Socket.IO for real-time communication.


Deployed link: [chirpy-chat](chttingapp.netlify.app/)


## Features

- Group messaging: Users can create groups and send messages to multiple participants.
- Personal messaging: Users can have one-on-one conversations with other users.
- User search: Users can search for other users and initiate conversations.
- Emoji support: Users can send emojis in their messages.
- Admin privileges: Only administrators can add people to groups.
- Authentication and authorization: JWT-based authentication system to ensure secure access.
- Toast notifications: React-Toastify for displaying user-friendly notifications.

Installation

* Clone the repository:

 ``` bash```

```bash 
git clone https://github.com/your-username/chat-application.git 
``` 

- Change to the project directory:

```bash
cd chat-application
```
* Install dependencies:
```bash
npm install
```

## Configure the application:

Update the .env files in both frontend and backend
- For frontend; 
```json

REACT_APP_URL=http://localhost:4000

```

- For backend:
```json

PORT=4000
MONGODB_URI= your mondodburl
JWT_SECRET=yoursecret
JWT_LIFETIME= 40m


```

## Start the development server:
```bash
    npm run dev
```

Open your browser and navigate to http://localhost:3000 to access the application.

## Technologies Used

   - Front-end:
        * ***React***: JavaScript library for building user interfaces.
        * ***Socket.IO***: Real-time communication library.
        * ***React-Toastify***: Library for displaying toast notifications.
        * ***HTML5 and CSS3***: Markup and styling of the application.
   - Back-end:
        * ***Node.js***: JavaScript runtime environment.
        * ***Express***: Web application framework for Node.js.
        * ***MongoDB***: NoSQL database for storing user information and chat messages.
        * ***Socket.IO***: Real-time communication library.
        * ***Bcrypt***: Library for password hashing and verification.
        * ***Validator***: Library for input validation.

## File Structure

``` 
├── frontend
│   ├── public
│   └── src
│       ├── components
│       ├── config
│       ├── context
│       ├── pages
│       ├── App.js
│       └── index.js
├── backend
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── index.js
│   └── .env
└── README.md
```
## Usage:

   - Register a new account:
        * Open the application in your browser.
        * Enter your name, email, and password.
        * Click on the "Register" button
        * Click on the "Submit" button to register your account.

   - Log in:
        * Enter your email and password.
        * Click on the "Submit" button to log in.

   - Start a new conversation:
        * Search for the user you want to chat with.
        * Click on the user's name to open the conversation.

   - Join or create a group:
        * Only administrators can add people to groups.
        * Create a new group or select an existing group.
        * Add users to the group to enable group messaging.


## Contributing
All contributions are welcome. 
