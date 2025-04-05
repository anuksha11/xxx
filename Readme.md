# VHire Iteration 1
Many companies face challenges in conducting interviews, as their tech teams are often engaged in the interview process voluntarily, which can lead to vague and inconsistent interviews and requires too much of their bandwidth for this. To address this, we propose developing software that outsources the first or technical round of interviews. This solution will benefit both candidates and companies by offering a seamless interview experience for applicants while making it easier for companies to shortlist candidates.Additionally, it will significantly reduce the effort required from engineering teams during the technical round of the hiring process.

## Technologies Used

- **React.js**: For the frontend framework
- **Zegocloud**: A real-time audio and video communication service used for video conferencing.
- **Node.js**: For backend development.
- **Tailwind CSS**: Styling framework
- **Socket.io**: For bidirectional communication between clients and servers.
- **FireBase** : Database

## Modules

## Features:

1. **User Authentication** – Secure login and registration for candidates, companies, and admins.
2. **Company Registration** – Companies can register, post job openings, and view a filtered list of candidates.
3. **Candidate Management** – Companies can shortlist and access candidate profiles and resumes.
4. **Collaborative Code Editor and Compiler** – In-browser coding rounds powered by a One Compiler and Code Mirror API .
5. **Chatbot** - Chatbot to help assist the interviewers.
6. **Video Conferencing Engine** – Seamless video interviews using the Zego Cloud API.
7. **Report Generation** by the Interviewer

## How to use the apis:
### Gemini API:
1. Open the link "https://aistudio.google.com/u/1/apikey" and signup with your gmail.
2. Click on Create API Key
3. Copy the API Key
   
### One Compiler API:
1. Open "https://rapidapi.com" in your browser and signup with your gmail.
2. In the "Search APIs" button type One Compiler APIs and select the api.
3. Copy the "X-RapidAPI-Key"
   
## Steps to run the application
### Steps to run the backend:
1. ```bash
   git clone https://github.com/anuksha11/VHire.git
   ```
2. ```bash
   cd VHire
   ```
3. ```bash
   git checkout iteration-2
   ```
4. To change the directory
   ```bash
   cd vhire-it-1 (change directotry)
   ```
5. ```bash
   cd backend
   ```   
6. ```bash
   npm install (to install all node modules)
   ```
7. Create a .env file in the backend directory.
8. Paste the following in the .env file(paste your gemini and one compiler api keys along with this)
   ```
   GOOGLE_GENAI_API_KEY=
   RAPIDAPI_KEY=
   RAPIDAPI_HOST=onecompiler-apis.p.rapidapi.com
   ONE_COMPILER_API_URL=https://onecompiler-apis.p.rapidapi.com/api/v1/run
   ```
9. Run the command:
   ```bash
   npm start (to run the backend)
   ```

### Open new Terminal(For Running Frontend):
1. 
   ```bash
   cd vhire-it-1 (change directotry)
   ```
3. ```bash
   cd vhire-interview-platform
   ```
4. ```bash
   npm install (to install all node modules)
   ```
5. ```bash
   npm start (to run the frontend)
   ```


