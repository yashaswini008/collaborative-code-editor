# collaborative-code-editor
A real-time collaborative code editor built with Monaco Editor, Yjs, and a WebSocket server. This project enables multiple users to edit code simultaneously, offering a seamless and interactive coding experience.
Features
Multiple File Support: Work with multiple files in a structured folder layout.
Yjs Connection: Real-time collaboration across multiple files using Yjs.
Authentication: Secure user authentication is implemented.
Room Creation: Dynamic room creation for collaboration sessions.
Todo List
 Multiple files
 Yjs connection for multiple files
 Authentication done
 Room creation
 Saving files to the server after all clients leave the Yjs instance
 Running code in a container
 Support for WebRTC
 Add other features or tasks needed here
Getting Started
Prerequisites
Node.js
Yarn or npm
Installation
 cd server/
 node server.js
 node websocket.js
   cd client/
   npm run dev
