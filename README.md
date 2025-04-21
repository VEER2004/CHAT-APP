# AQUA-VITAE-CHAT

A modern, medical-aesthetic responsive chat application built with React, Tailwind CSS, and a beautiful custom UI.

## Overview

AQUA-VITAE-CHAT is a real-time communication platform designed for healthcare professionals and patients, featuring a clean, professional UI with a medical aesthetic. The application supports multiple chat rooms, persistent messaging, and formatted text communication.

## Features

- **User Authentication**: Simple username-based login system
- **Multiple Chat Rooms**: Pre-defined and custom rooms
- **Real-time Messaging**: Immediate message delivery
- **Message Formatting**: Support for basic text formatting (bold, italic)
- **Responsive Design**: Works on desktop and mobile devices
- **Medical Aesthetic**: Clean, professional design with medical color scheme

## Technology Stack

- React 18 with TypeScript
- Tailwind CSS
- shadcn/ui components
- React Context API for state management
- WebSocket communication

## Getting Started

1. Clone the repository
   ```
   git clone https://github.com/VEER2004/CHAT-APP.git
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Start the development server
   ```
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Documentation

For detailed technical documentation, please refer to [AQUA-VITAE-CHAT Technical Project Documentation](./AQUA-VITAE-CHAT_Technical_Project_Documentation.md).

## Project Structure

```
chat-application/
│
├── index.html                  # Main HTML file (structure of the app)
├── assets/
│   ├── images/                 # Folder for any images/icons you may use
│   └── styles/                 # Folder for CSS files
│       └── main.css            # Main stylesheet for the app
├── js/
│   ├── app.js                  # Main JavaScript logic (client-side WebSocket handling)
│   ├── websocket.js            # WebSocket connection and message handling
│   └── utils.js                # Utility functions like input validation or message formatting
├── server/
│   ├── server.js               # Node.js WebSocket server setup (using 'ws' or 'socket.io')
│   └── routes/                 # Folder for any REST API routes (if applicable)
├── package.json                # Node.js dependencies and scripts
├── README.md                   # Instructions for setup and running the application
└── .gitignore                  # Git ignore file to exclude node_modules, etc.
```

> Note: In this React-based starter, much of the structure is within `src/` but files like `/js/app.js` and `/server/server.js` can be added if/when WebSocket logic is implemented.

---

## Tech Stack

- React + Vite
- TypeScript
- Tailwind CSS (plus custom styles for chat bubbles/cards)
- shadcn-ui & lucide-react icons

---

## To Add WebSocket/Backend functionality

- You can create the `js/` and `server/` folders at project root as per the above structure, using Node.js and your preferred WebSocket library (`ws`/`socket.io`).
