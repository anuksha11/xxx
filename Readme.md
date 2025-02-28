# VHire-iteration-1

## Technologies Used

- **React.js**: For the frontend framework
- **Zegocloud**: A real-time audio and video communication service used for video conferencing.
- **Node.js**: For backend development.
- **CSS**: Styling framework
- **Socket.io**: For bidirectional communication between clients and servers.

## Modules

- **video_conferencing**: Contains code for the video conferencing part of our application.
- **collaborative_editor_sample_2**: Contains code for the collaborative code editor and compiler.

## Installation and Setup
### Prerequisites
1. Node.js v20.10.0+ installed in your system


### Steps to Run the Video Conferencing Application
1. Download the Zip File

2. Navigate to the `video_conferencing` directory:
   ```bash
   cd video_conferencing
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open the application in your browser:
   ```
   http://localhost:3000
   ```

### Steps to Run the Collaborative Code Editor Application
1. Download the Zip File

2. Navigate to the `collaborative_editor_sample_2` directory:
   ```bash
   cd collaborative_editor_sample_2
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Run the frontend:
   ```bash
   cd collaborative-editor
   npm run dev  # Run again to open two different frontend instances
   ```
5. Run the backend:
   ```bash
   node server.js
   ```
6. Open the application in your browser:
   ```
   http://localhost:5173
   http://localhost:5174
   ```
