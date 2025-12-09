Nexora

Nexora is a modern SaaS platform that gives users powerful AI-driven creative tools, subscription-based premium access, and a vibrant community space to share and explore creative work.

🌍 Live Demo: https://nexora-saas-tau.vercel.app

🚀 Features

🔐 Authentication with Clerk
Secure email/password + social login support.

💳 Subscription Management
Seamless premium upgrades and payment handling.

🤖 AI-powered Tools

Google Gemini API for text, content, and creative generation

ClipDrop API for image editing, removal, enhancements, and more

🌐 Community Creations Tab
Explore what other users are building inside Nexora.

🛠 Tech Stack

Frontend: Vite + React

Backend: Node.js

Database: NeonDB (SQL)

Authentication: Clerk

APIs: Google Gemini API, ClipDrop API

UI Components: Aceternity UI

Deployment: Vercel

📦 Installation

Clone the repository and install dependencies:

git clone https://github.com/MdAyanBadar/Nexora.git
cd Nexora
npm install

⚙️ Environment Variables
Create a .env file in the server directory:
PORT=server_port_number
NODE_ENV=development

# Database
DATABASE_URL=<your-NeonDB_URL>

# Authentication
CLERK_PUBLISHABLE_KEY=<your-clerk-publishable-key>
CLERK_SECRET_KEY=<your-clerk-secret-key>

# AI APIs
GEMINI_API_KEY=<your-google-gemini-api-key>
CLIPDROP_API_KEY=<your-clipdrop-api-key>

# Cloud Storage
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_secret_key>

Create a .env file in the client directory:
VITE_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
VITE_BASE_URL=http://localhost:3000/api

🏃‍♂️ Running Locally

Start the frontend:

cd client
npm run dev


Start the backend:

cd server
nodemon server.js

🌐 Deployment

The project is deployed on Vercel.
Check out the Live Demo 🌐: https://nexora-saas-tau.vercel.app

📄 License

This project is open source and available under the MIT License.

👨‍💻 Author

Created by Ayan Badar
If you like this project, ⭐ the repository on GitHub!# Nexora
