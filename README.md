🏋️‍♂️ AI Fitness & Calories Tracker (Website)
🌐 Live Website:
https://akhusro30-maker.github.io/Ai-Fitness-and-Calories-tracker/
A browser-based fitness tracking website that allows users to log meals, track macros, record lifts, and monitor progress — enhanced with AI-powered nutrition estimation.
This is a client-side website (no mobile app) built using modern web technologies and deployed via GitHub Pages.
🌟 What This Website Does
🍽️ Nutrition Tracking
AI-powered food estimation using natural language input
Photo-based meal analysis using your device camera
Manual food entry for full control
Tracks calories, protein, carbs, and fat
🏋️ Strength Training Logs
Log exercises with weight and reps
Mark main lifts for weekly progress tracking
Automatically shows weekly personal bests
📊 Progress & Goals
Set daily calorie and protein goals
View daily summaries and weekly progress
Simple, clean dashboard for consistency
🔐 User Data
Anonymous sign-in via Firebase Authentication
Each visitor gets private, persistent data storage
🧠 AI Features
Powered by Google Gemini AI:
Converts food descriptions into structured macro data
Supports image + text inputs for better estimates
🛠️ Tech Stack
Layer	Technology
Website	HTML, Tailwind CSS, Vanilla JavaScript
Database	Firebase Firestore
Auth	Firebase Anonymous Authentication
AI	Google Gemini API
Hosting	GitHub Pages
🚀 Live Demo
👉 https://akhusro30-maker.github.io/Ai-Fitness-and-Calories-tracker/
No installation required — runs directly in the browser.
⚙️ Local Setup (Optional)
git clone https://github.com/akhusro30-maker/Ai-Fitness-and-Calories-tracker.git
cd Ai-Fitness-and-Calories-tracker
open index.html
🔐 Configuration Notes
To enable AI features locally, update in index.html:
const YOUR_FIREBASE_CONFIG = { /* your Firebase config */ };
const GEMINI_API_KEY = "YOUR_GEMINI_API_KEY";
⚠️ API keys should not be exposed in production deployments.
📷 Camera Usage
Camera access is optional
Used only for food image analysis
Prefers rear camera on supported devices
🎯 Project Purpose
This project demonstrates:
Frontend engineering with vanilla JS
Realtime databases and auth
AI API integration
Clean UI with Tailwind CSS
Deployment using GitHub Pages
Ideal as a portfolio project.
