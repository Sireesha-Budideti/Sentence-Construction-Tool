# 🧠 Sentence Construction Tool

An interactive quiz that challenges users to complete sentences using the correct words. Built with React, Vite, Tailwind CSS, and TypeScript.

---

## 🌐 Live Demo

🔗 [View Demo]([https://your-netlify-link.netlify.app](https://thunderous-creponne-b57993.netlify.app/))  

---

## 🛠 Tech Stack

- React
- Vite
- Tailwind CSS
- TypeScript
- shadcn/ui
- JSON Server (local mock API)

---

## 📦 Installation

To get started, clone this repository and install the dependencies:

```bash
git clone https://github.com/Sireesha-Budideti/Sentence-Construction-Tool.git
cd Sentence-Construction-Tool
npm install

▶️ Running Locally
1. Start the React App
bash
Copy
Edit
npm run dev
This will start the development server and the app will be available at http://localhost:3000.

2. Start JSON Server
To run the mock API server locally, use the following commands:

bash
Copy
Edit
npm install -g json-server
json-server --watch src/data/questions.json --port 3001
This will start the JSON Server and the API will be available at http://localhost:3001/questions.

The app will fetch question data from the mock API running on http://localhost:3001.

🚀 Deploying to Netlify
To deploy this app on Netlify:

Push your project to GitHub (already done ✅).

Go to Netlify and click on “Add new site” → “Import from Git”.

Select your repository.

Set the following build settings:

Build command: npm run build

Publish directory: dist

Click Deploy Site.

Once deployed, copy the Netlify URL and add it to the Live Demo section above.

👩‍💻 Author
Sireesha Budideti
GitHub: @Sireesha-Budideti

