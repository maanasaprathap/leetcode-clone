
# 🧠 LeetCode Clone

A full-featured LeetCode clone built with **Next.js**, **React**, **Tailwind CSS**, **TypeScript**, **Recoil**, and **Firebase**. This project allows users to sign up, log in, solve algorithm problems, and track their submissions – mimicking the experience of LeetCode.

> 🎥 Built following [@codesistency](https://www.youtube.com/@codesistency)'s project tutorial  
> 🔗 [Watch full tutorial](https://www.youtube.com/watch?v=HhZTIh3e-KY)

---

## 🚀 Live Demo

👉 [https://leetclone.vercel.app/problems](https://leetclone.vercel.app/problems)

---

## 🧰 Tech Stack

- **Frontend**: React.js, TypeScript, Tailwind CSS
- **State Management**: Recoil
- **Routing & Rendering**: Next.js (SSG/SSR)
- **Authentication**: Firebase Auth
- **Database**: Firebase Firestore
- **Code Editor**: Monaco Editor
- **Deployment**: Vercel

---

## 🖼️ Features

- ✅ User authentication (signup, login, password reset)
- 🧩 Browse and attempt coding problems
- 🧠 Monaco-based live code editor
- 🧪 Custom test cases & output feedback
- 📦 Auto-save user code in localStorage
- 🌟 Like, dislike, star problems
- 🎉 Confetti celebration on success
- 🔄 Next/Previous problem navigation
- 🧾 User stats and submission tracking
- 🔒 Firebase security rules

---

## 📂 Project Structure


---

## 🧪 Problems Implemented

- Two Sum  
- Reverse Linked List  
- Jump Game  
- Valid Parentheses  
- Search in 2D Matrix  
- ... and more added in Firestore

---

## 📦 Local Setup

```bash
# Clone the repository
git clone https://github.com/your-username/leetcode-clone.git
cd leetcode-clone

# Install dependencies
npm install

# Set up Firebase environment variables
touch .env.local
# Add the following Firebase config values to .env.local
# NEXT_PUBLIC_FIREBASE_API_KEY=...
# NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=...
# NEXT_PUBLIC_FIREBASE_PROJECT_ID=...
# etc.

# Run the development server
npm run dev
