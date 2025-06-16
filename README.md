# IntervuAI

<div align="center">

<img src="./public/logo.svg" alt="VoxNavi Logo" width="120" />

<h2>AI-Powered Interview Preparation Platform</h2>

<p>
IntervuAI is a modern, responsive web application designed to help job seekers prepare for interviews through AI-powered mock interviews and detailed feedback.
</p>

</div>

<div align="center">

[![Next.js](https://img.shields.io/badge/Next.js-15.2.3-black)](https://nextjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-11.5.0-orange)](https://firebase.google.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/)

</div>

## 🔗 Live Demo

Experience VoxNavi in action: [Live Link](https://vox-navi.vercel.app/)

## 📱 Home Page

![Home Page](/public/homepage.png "Homepage")

## 🤵🏻 Interview Page

![Interview Page](/public/Interview.png "Interview page")

## ✨ Features

- **AI Voice Interviews**: Practice with Vapi's voice assistant for a realistic interview experience
- **Customizable Interviews**: Generate interviews tailored to specific job roles, experience levels, and tech stacks
- **Comprehensive Feedback**: Get detailed assessments powered by Google's Gemini AI
- **User Authentication**: Secure signup and login system via Firebase Authentication
- **Interview Library**: Access and attempt interviews created by other users
- **Dark Mode Design**: Modern, sleek UI with responsive design for all devices
- **Detailed Performance Analytics**: View scores across multiple categories including communication skills, technical knowledge, and problem-solving
- **Privacy Control**: Option to delete all user data upon account deletion

## 🛠️ Tech Stack

- **Frontend**: Next.js 15, React 19, Tailwind CSS 4
- **UI Components**: shadcn/ui
- **Backend**: Next.js API Routes, Firebase Admin SDK
- **Database**: Firebase Firestore
- **Authentication**: Firebase Auth
- **Form Validation**: Zod, React Hook Form
- **AI Services**:
  - Voice Assistant: Vapi AI
  - Feedback Generation: Google Gemini
  - Interview Questions: OpenAI
- **Deployment**: Vercel

## 📚 Project Structure

```
vox-navi-next15-app/
├── app/                  # Next.js pages and API routes
├── components/           # Reusable React components
├── constants/            # Application constants
├── firebase/             # Firebase configuration and utils
├── lib/                  # Utility functions and hooks
├── public/               # Static assets
├── types/                # TypeScript type definitions
└── ...config files
```

## 📊 Interview and Feedback System

1. **Interview Generation**:

   - Custom interviews based on job role, experience level, and tech stack
   - Questions generated using AI models

2. **Voice Interview Process**:

   - Real-time voice interaction with the AI assistant
   - Transcript recording for feedback generation

3. **Feedback Analysis**:
   - Multiple performance categories assessment
   - Strengths and areas for improvement
   - Overall score and detailed recommendations
