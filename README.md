🧙‍♂️ Code Wizard
Code Wizard is an elegant and AI-powered code review web application built with React. It lets developers paste code, get instant reviews from an AI model, and visualize the feedback in a beautifully styled interface. Perfect for improving code quality quickly and interactively.

📸 Demo
<img width="1440" alt="Screenshot 2025-04-29 at 7 38 43 AM" src="https://github.com/user-attachments/assets/7479a3ad-c764-4656-a77d-af393442b2b6" />


🚀 Features
⚡ Live code editing with syntax highlighting (powered by react-simple-code-editor and prismjs)

🤖 AI-based code review using an external backend API

📱 Fully responsive across devices

✨ Highlighted markdown feedback using react-markdown and rehype-highlight

📦 Tech Stack
Frontend: React, PrismJS, Tailwind-like modern CSS

Code Editor: react-simple-code-editor

Syntax Highlighting: prismjs, highlight.js

Markdown Rendering: react-markdown, rehype-highlight

AI Review API: Axios to communicate with a local or cloud-based AI server

📁 Folder Structure
bash
Copy
Edit
/public
/src
  ├── App.jsx
  ├── index.css
  ├── main.jsx
  ├── App.css
⚙️ Getting Started
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/Sujal1023/Code-wizard.git
cd Code-wizard
2. Install dependencies
bash
Copy
Edit
npm install
3. Run the app
bash
Copy
Edit
npm run dev
App will be live at http://localhost:5173

🌐 API Setup
Make sure your AI backend is running at http://localhost:3000/ai/get-review.

If needed, you can mock or replace it with your own API logic.

📄 Example Code Snippet
javascript
Copy
Edit
function sum() {
  return 1 + 1;
}
🧠 AI Review Sample Output
✅ Your function is simple and correct.
🛠 Consider adding parameter support and type safety.

🤝 Contribution
Contributions, suggestions, and stars are welcome! Feel free to fork and submit pull requests.

📃 License
MIT License © Sujal1023

