# WebRTC Screen Share Application

## Overview
This repository contains an application that demonstrates how to implement screen sharing using WebRTC. It allows users to share their screen in real-time with other participants.

## Features
- Real-time screen sharing
- Multi-user support
- Cross-platform compatibility
- Easy to integrate into existing applications

## Architecture
The application is structured into several components:
- **Client**: The frontend where users interact and share screens.
- **Signaling Server**: Manages connections between clients and facilitates communication.
- **WebRTC**: Handles peer-to-peer communication for real-time screen sharing.

## Deployment
### Prerequisites
- Node.js (version >= 14)
- npm (version >= 6)
- A WebRTC-compatible browser (Chrome, Firefox, etc.)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/oyolonile/webrtc-screenshare.git
   cd webrtc-screenshare
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the signaling server:
   ```bash
   node server.js
   ```
4. Open the application in your browser at `http://localhost:3000`.

## Setup
1. Ensure that you have a working environment with Node.js and npm installed.
2. Follow the deployment steps to get the application up and running.

## API Documentation
### Signaling API
- **POST /join**: Join a room to start sharing your screen.
- **POST /signal**: Send signaling data to other peers.

### Peer Connection API
- **startSharing()**: Starts sharing the user's screen.
- **stopSharing()**: Stops the screen sharing.

For further information, check the inline documentation in the codebase.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.