# VoiceSphere
VoiceSphere
VoiceSphere is a live streaming audio podcast platform designed for seamless and high-quality voice communication. It offers two modes: Public and Social. In Public mode, anyone can join the stream, and it appears on the homepage along with the discussion topic. In Social mode, the stream is private, and only users with the link can join, similar to Google Meet.

Live Demo
You can view the live demo of the project here.

Features
Live Streaming Audio: High-quality voice communication using WebRTC.
Public Mode: Open to all, visible on the homepage with topic search functionality.
Social Mode: Private streaming, accessible only via shared link.
Advanced Audio Processing: Echo cancellation, noise suppression, and auto gain control for optimal audio quality.
Dependencies
Frontend
@reduxjs/toolkit
@testing-library/jest-dom
@testing-library/react
@testing-library/user-event
axios
dsp.js
freeice
mdb-react-ui-kit
nodemailer
react
react-dom
react-redux
react-router-dom
react-scripts
react-toastify
socket.io-client
web-vitals
Backend
bcrypt
body-parser
cookie-parser
cors
dotenv
express
jimp
jsonwebtoken
mongoose
nodemailer
nodemon
socket.io
twilio
Installation
Prerequisites
Node.js
npm
Setup
Clone the repository:

git clone https://github.com/jayesh-unde/VoiceSphere.git
cd VoiceSphere
Install frontend dependencies:

cd frontend
npm install
Install backend dependencies:

cd ../backend
npm install
Running the Application
Start the backend server:

cd backend
nodemon server.js
Start the frontend server:

cd ../frontend
npm start
Usage
Public Mode:

Open the homepage to see ongoing public streams.
Use the search bar to find a specific topic.
Click on a stream to join and participate in the discussion.
Social Mode:

Create a private stream and share the link with intended participants.
Only users with the link can join the stream.
Contributing
We welcome contributions from the community. Please follow these steps:

Fork the repository.
Create a new branch for your feature or bugfix.
Commit your changes and push the branch to your fork.
Open a pull request with a detailed description of your changes.
Contact
For support or inquiries, please contact [jayeshunde2002@gmail.com].

Additional Information
This project uses advanced audio processing features to ensure high-quality voice communication. The following WebRTC options are used:

echoCancellation: true
noiseSuppression: true
autoGainControl: true
To further optimize the audio quality, the Opus codec is prioritized during the SDP negotiation process.

Feel free to modify this README as per your specific needs or any additional details you may want to include.
