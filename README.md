# 📡 ConnectNow

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D14.0.0-brightgreen.svg)](https://nodejs.org/)
[![Socket.io](https://img.shields.io/badge/Socket.io-4.5.4-black.svg)](https://socket.io/)

**ConnectNow** is a modern, lightweight video conferencing application built with **WebRTC**, **Socket.io**, and **Node.js**. It enables seamless real-time communication with support for multiple participants, screen sharing, and recording features.

> [!NOTE]
> This implementation is optimized for small groups (up to 4 participants) to ensure the best performance and low latency.

---

## 🚀 Key Features

- 🎥 **Multi-Participant Video**: Concurrent video streams for group meetings.
- 🎤 **Audio Control**: Quick toggle for muting/unmuting audio.
- 🖥️ **Screen Sharing**: Share your desktop or specific windows with other participants.
- 💬 **Real-time Chat**: Integrated text chat for instant messaging during calls.
- 🔇 **Individual Muting**: Option to mute specific participants on your end.
- 🔍 **Flexible Layout**: Expand or collapse participant streams for focus.
- ⏺️ **Recording Capabilities**: Built-in support for both screen and video recording.

---

## 🛠️ Tech Stack

- **Backend**: [Node.js](https://nodejs.org/), [Express](https://expressjs.com/)
- **Real-time Communication**: [Socket.io](https://socket.io/), [WebRTC](https://webrtc.org/)
- **Styling & UI**: Vanilla CSS, HTML5
- **Utilities**: [Nodemon](https://nodemon.io/) (for development)

---

## 📂 Project Structure

```text
.
├── src/
│   ├── app.js          # Server entry point
│   ├── index.html      # Main application interface
│   ├── assets/         # Static styles, images, and logic
│   │   ├── app.css     # Main stylesheet
│   │   └── js/         # Frontend RTC and helper logic
│   └── ws/             # WebSocket/Socket.io stream signaling
├── package.json        # Dependencies and scripts
└── README.md           # Documentation
```

---

## 🏁 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) (comes with Node.js)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/namanviber/ConnectNow.git
   cd ConnectNow
   ```

2. **Install dependencies**:
   ```bash
   npm ci
   ```

### Running the Application

1. **Start the server**:
   ```bash
   npm start
   ```
   *Alternatively, for development with auto-reload:*
   ```bash
   npm run watch
   ```

2. **Access the app**:
   Open your browser and navigate to `http://localhost:3000`.

---

## 🌐 Demo

You can try the live version of ConnectNow here:  
👉 **[Live Demo](https://connectnow.onrender.com)**

---

## 📄 License

This project is licensed under the **ISC License**. See the `package.json` for details.


