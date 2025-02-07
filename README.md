# 🧠 React Quiz App

## 📌 Overview
**React Quiz App** is an interactive quiz application built with **React**, utilizing the `useReducer` hook for efficient state management. The quiz has a **global timer** and an **automatic result screen**, making it engaging and time-sensitive.

## 🚀 Features
- ❓ **Dynamic Questions:** Users answer a set of **15 multiple-choice questions**.
- ⏳ **Global Quiz Timer (7.5 Minutes):**  
  - The entire quiz runs on a **single timer of 15 × 30 seconds (7.5 minutes)**.  
  - When time runs out, the quiz automatically **ends and shows the result**.  
- 🏆 **Score Tracking & Result Page:**  
  - The final score is calculated based on correct answers.  
  - The result page provides feedback on performance.  
- 🔄 **State Management with `useReducer`:**  
  - Manages **current question, selected answers, remaining time, and score**.  
  - Ensures smooth quiz progression and automatic result transition.  
- 🎨 **User-Friendly Interface:** Clean, responsive, and easy to navigate.

## 🛠️ Tech Stack
- **Frontend:** React.js (`useReducer`, `useState`, `useEffect`)
- **Styling:** CSS for layout and design

## ⚙️ How It Works
1. **State Management:**  
   - `useReducer` tracks quiz progress, user answers, and score.  
   - The quiz auto-progresses based on user input or **time expiration**.  

2. **Timer System:**  
   - A **global timer (7.5 minutes)** limits the entire quiz duration.  
   - The quiz **automatically ends** when time runs out, even if questions remain unanswered.  
   - If the user finishes early, the result is displayed immediately.  

3. **Result Calculation:**  
   - The final score is displayed based on the number of correct answers.  
   - Users receive a summary of their performance.
