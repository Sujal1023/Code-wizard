Code Wizard
AI-Powered Code Review Web Application

Code Wizard is an elegant and AI-powered code review web application built with React. It allows developers to paste code, receive instant reviews from an AI model, and visualize feedback in a beautifully styled interface. It's perfect for improving code quality quickly and interactively.

🚀 Features
Live Code Editing: Real-time code editing with syntax highlighting powered by react-simple-code-editor and prismjs.

AI-Based Code Review: Instant code analysis using an external backend AI API.

Responsive Design: Fully responsive interface compatible with various devices.

Markdown Feedback Rendering: Highlighted markdown feedback using react-markdown and rehype-highlight.

🛠️ Tech Stack
Frontend: React, Tailwind-like modern CSS

Code Editor: react-simple-code-editor

Syntax Highlighting: prismjs, highlight.js

Markdown Rendering: react-markdown, rehype-highlight

API Communication: Axios for interacting with a local or cloud-based AI server

📁 Folder Structure
css
Copy
Edit
Code-wizard/
├── public/
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── BackEnd/
│   └── [Backend files and modules]
├── Frontend/
│   └── [Frontend files and modules]
├── README.md
└── package.json
⚙️ Getting Started
Prerequisites
Ensure you have the following installed:

Node.js (v14 or higher)

npm (v6 or higher)

Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Sujal1023/Code-wizard.git
cd Code-wizard
Install Dependencies

bash
Copy
Edit
npm install
Start the Application

bash
Copy
Edit
npm run dev
The application will be accessible at http://localhost:5173.

Backend Setup
If your project includes a backend:

Navigate to the BackEnd directory:

bash
Copy
Edit
cd BackEnd
Install backend dependencies:

bash
Copy
Edit
npm install
Start the backend server:

bash
Copy
Edit
npm run start
Ensure the backend server is running before using the frontend application.

🧪 Usage
Open the application in your browser at http://localhost:5173.

Paste your code into the editor.

Click the "Review" button to receive AI-generated feedback.

Review the feedback displayed below the editor.

📸 Screenshots
<img width="1440" alt="Screenshot 2025-04-29 at 7 38 43 AM" src="https://github.com/user-attachments/assets/7479a3ad-c764-4656-a77d-af393442b2b6" />

Note: Replace the above link with the actual path to your screenshot image.

📝 License
This project is licensed under the MIT License.

🙏 Acknowledgements
react-simple-code-editor

prismjs

react-markdown

rehype-highlight

