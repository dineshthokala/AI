# AI Learning Assistant

A modern, AI-powered web application to help students and educators generate quizzes, evaluate answers, and track academic progress. Built with React, Firebase, and Tailwind CSS.

## Features

- **AI Question Generator:** Upload textbooks (PDFs) and automatically generate practice questions.
- **Smart Evaluation:** Instantly evaluate your written answers against model answers.
- **Web Search:** Get concise, AI-generated answers to academic questions from across the web.
- **Progress Analytics:** Visualize your learning progress and identify weak areas.
- **Voice Control:** Navigate and interact with the dashboard using voice commands.
- **Chat/Forum:** Interact with teachers and students in a collaborative environment.

## Tech Stack

- **Frontend:** React, Tailwind CSS, Framer Motion, React Hot Toast, React Router
- **Backend:** Python (Flask or FastAPI, not included here)
- **Authentication & Storage:** Firebase Auth, Firestore, Firebase Storage

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- Python (for backend, not included in this repo)

### Installation

1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd AI/frontend
   ```

2. **Install dependencies:**
   ```sh
   npm install
   # or
   yarn install
   ```

3. **Configure Firebase:**
   - Update `src/firebase.js` with your Firebase project credentials.

4. **Start the development server:**
   ```sh
   npm start
   # or
   yarn start
   ```
   The app will run at [http://localhost:3000](http://localhost:3000).

5. **Backend:**
   - Start the backend server (see `../backend/README.md` if available).
   - By default, the frontend expects the backend at `http://localhost:5002` for web search and PDF processing endpoints.

## Project Structure

```
frontend/
  src/
    components/      # Reusable UI components
    hooks/           # Custom React hooks
    pages/           # Main page components (Home, Auth, Dashboard)
    assets/          # Static assets (logo, images)
    firebase.js      # Firebase config
    index.js         # App entry point
    index.css        # Tailwind and custom styles
  public/            # Static public files
  tailwind.config.js # Tailwind CSS config
  ...
backend/
  server.py          # Backend server (Flask/FastAPI)
  requirements.txt   # Python dependencies
```

## Customization
- **Branding:** Replace `src/assets/logo.png` with your own logo.
- **Firebase:** Update `src/firebase.js` with your Firebase credentials.
- **Backend:** Adjust API endpoints in frontend code if your backend runs on a different port or path.

## Deployment
- Build the frontend for production:
  ```sh
  npm run build
  ```
- Deploy the `build/` folder to your preferred hosting (Vercel, Netlify, Firebase Hosting, etc).

## License

This project is for educational purposes. See `LICENSE` for more details.

---

**Made with ❤️ for students and educators.**
