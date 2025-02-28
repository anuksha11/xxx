# VHire Iteration 1
Many companies face challenges in conducting interviews, as their tech teams are often engaged in the interview process voluntarily, which can lead to vague and inconsistent interviews and requires too much of their bandwidth for this. To address this, we propose developing software that outsources the first or technical round of interviews. This solution will benefit both candidates and companies by offering a seamless interview experience for applicants while making it easier for companies to shortlist candidates.Additionally, it will significantly reduce the effort required from engineering teams during the technical round of the hiring process.

## Technologies Used

- **React.js**: For the frontend framework
- **Zegocloud**: A real-time audio and video communication service used for video conferencing.
- **Node.js**: For backend development.
- **Tailwind CSS**: Styling framework
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
3. Install the dependencies for front end:
   ```bash
   npm install
   ```
4. Navigate to the front-end folder:
   ```bash
   cd collaborative-editor
   ```
5. Install the dependencies for backend:
   ```bash
   npm install
   ```
6. Run the frontend:
   ```bash
   cd collaborative-editor
   npm run dev  # Repeat the steps 2,3,4,6 in another terminal to open two different frontend instances
   ```
7. Run the backend:
   ```bash
   #open a new termina
   cd collaborative_editor_sample_2
   node server.js
   ```
9. Open the application in your browser:
   ```
   http://localhost:5173
   http://localhost:5174
   ```
