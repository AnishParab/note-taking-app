# About the App
- A simple, lightweight note-taking app with Markdown support. Write, edit, and store your notes seamlessly with a clean interface.

---
# Tech-stack
- NextJS 15 ---> React framework for building the app.
- Vanilla CSS ---> Implemented a retro-arcade look.
- Firebase ---> Authentication and cloud-based data storage.

---
# Features
- Create and edit notes using Markdown.
- Secure user authentication with Firebase.
- Save and sync notes across devices with cloud storage.
- Clean and minimal UI powered by Vanilla CSS.

---
# Getting Started

## Prerequisites
- Node.js (v18 or later)
- Firebase project setup (API keys required)

## Installation
``` bash
# Clone the repository
git clone https://github.com/AnishParab/note-taking-app

# Navigate into the project
cd note-taking-app

# Install dependencies
npm install
```

## Running the app
``` bash
# Start development server
npm run dev
```

- The app will be available at http://localhost:3000

---
# Configuration
- Create a `.env.local` file in the project root and add your Firebase configuration:
``` env
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project_id.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project_id.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
```

---
# Deployment
- This project can be easily deployed on Vercel for free.

---


