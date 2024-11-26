Resume Builder
Overview
The Resume Builder is a web application that allows users to create, edit, and download their resumes. It utilizes a modern tech stack including React for the frontend and Node.js with Express for the backend, along with MongoDB for data storage. Users can sign up, log in, and manage their resume information seamlessly.

Features
User Authentication: Users can sign up and log in using Google authentication.
Resume Creation: Users can input their personal information, education, work experience, projects, skills, and interests to create a comprehensive resume.
PDF Generation: Users can generate their resumes as PDF files for easy sharing and printing.
Data Persistence: User data is stored in a MongoDB database, allowing users to save their progress and retrieve it later.
Tech Stack
Frontend: React, Material-UI, Axios
Backend: Node.js, Express
Database: MongoDB
PDF Generation: html-pdf
Authentication: Google OAuth2
Installation
Prerequisites
Node.js
MongoDB
A Google Developer account to set up OAuth2 credentials
Clone the Repository
bash

Verify

Open In Editor
Edit
Copy code
git clone https://github.com/yourusername/Resume-Builder.git
cd Resume-Builder
Backend Setup
Navigate to the backend folder:

bash

Verify

Open In Editor
Edit
Copy code
cd server
Install dependencies:

bash

Verify

Open In Editor
Edit
Copy code
npm install
Create a .env file in the server directory and add your environment variables:

plaintext

Verify

Open In Editor
Edit
Copy code
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
MONGO_URI=your_mongodb_connection_string
PORT=4000
Start the server:

bash

Verify

Open In Editor
Edit
Copy code
node server.js
Frontend Setup
Navigate to the frontend folder:
bash

Verify

Open In Editor
Edit
Copy code
cd client
Install dependencies:
bash

Verify

Open In Editor
Edit
Copy code
npm install
Start the React application:
bash

Verify

Open In Editor
Edit
Copy code
npm start
Usage
Navigate to http://localhost:3000 in your web browser.
Sign up or log in using Google authentication.
Fill out the resume form with your details.
Save your progress and download your resume as a PDF.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License
This project is licensed under the MIT License.

Acknowledgments
Thanks to the developers of the libraries and frameworks used in this project.
Special thanks to the community for their support and feedback.
