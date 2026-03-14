# FocusTime — Pomodoro Timer App

FocusTime is a modern Pomodoro Timer application built with React and Vite, designed to help users improve productivity using the real Pomodoro Technique rules.

The project aims to simulate a complete focus management tool with sessions, breaks, themes, notifications, and persistent state.


## Tech Stack

This project is built using:

- Vite
- React
- TypeScript



## Core Concepts Used

The application was developed to practice and demonstrate advanced React concepts:

- Reusable Components
- Props and Component State
- React Hooks (useState, useEffect, useRef, etc.)
- Context API + useReducer for global state management
- React Router DOM for navigation
- Web Workers for background timer processing
- LocalStorage for data persistence



## Styling & UI

- CSS Modules for scoped styling
- Theme system (light/dark modes)
- Responsive layout
- Clean productivity-focused interface



## UX Features

- Toast notifications using React Toastify
- Form validation for user inputs
- Session feedback and alerts


## ⏱ Pomodoro Features

This app implements the real Pomodoro Technique rules:

- Configurable focus sessions
- Short breaks between sessions
- Long breaks after a set number of cycles
- Session tracking
- Persistent progress
- Accurate timer (runs even when tab is inactive)


## Performance & Background Processing

To ensure timer accuracy and performance:

- Web Workers are used to run the timer off the main thread
- Prevents timer drift when the tab is in the background
- Improves UI responsiveness



## Project Goals

This project was created to:

- Practice modern React architecture
- Apply real-world state management patterns
- Demonstrate frontend performance techniques
- Build a portfolio-quality productivity app



## ▶️ Getting Started

### Install dependencies

```bash
npm install