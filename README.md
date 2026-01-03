# TrekList
TrekList
TrekList is a modern, minimal to-do list application designed for trekking, travel, and packing workflows. It helps users organize items efficiently with a clean UI and powerful bulk actions.
Built with React and Vite, TrekList combines React Context API for shared UI state and Zustand for scalable, predictable state management.
Features
Add, complete, and remove items
Mark all items as complete or incomplete
Reset list to initial state
Remove all items at once
Clean, modern, and responsive UI
Lightweight and fast performance
 Tech Stack
React – component-based UI
Vite – fast development and build tooling
React Context API – global UI state management
Zustand – scalable application state management
Modern CSS – custom styling with a polished layout
Architecture Overview
Context API is used for shared UI concerns and global configuration.
Zustand manages the core application state (items, actions, mutations) in a simple and predictable store.
Components are modular and reusable for maintainability.
The app follows a clean separation of concerns between UI, state, and logic.
 Getting Started
Prerequisites
Node.js (v16 or later)
npm
Installation
git clone https://github.com/vanshikapariharr/TrekList.git
cd TrekList
npm install
Run locally
npm run dev
The app will be available at:
http://localhost:5173
