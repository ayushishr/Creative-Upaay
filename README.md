Creative Upaay – Kanban Task Manager
Creative Upaay is a modern Kanban board built with React, Redux, and Firebase Authentication. It enables users to organize tasks into stages like Todo, In Progress, and Done with smooth drag-and-drop interactions, filters, and an activity log for better productivity tracking.

Deployment link --- https://creative-upaay.vercel.app/

✨ Key Features
🔐 User Authentication
Secure sign-up and login using Firebase

Route protection and session persistence

Basic user profile management

📋 Kanban Workflow
Move tasks between stages via drag-and-drop

Filter tasks by due date or priority

Real-time activity feed to monitor task updates

Create tasks with optional deadlines and priority labels

💅 Interface & Experience
Clean, responsive UI with Tailwind CSS

Smooth transitions and user-friendly components

Visual task history and activity tracker

Modals, dropdowns, and intuitive form inputs

🧰 Tech Stack
React 18

Redux Toolkit – State handling

Firebase Auth – Secure login system

React Router DOM – SPA navigation

Tailwind CSS – Modern, utility-first design

SortableJS – Drag-and-drop functionality

Vite – Lightning-fast bundling and development

🗂️ Folder Structure Overview
bash
Copy
Edit
/src
  ├── /components        → Reusable UI elements
  ├── /context           → Custom context for auth state
  ├── /store             → Redux slices and config
  ├── /firebase          → Firebase integration
🧭 Development Workflow
1. UI-First Strategy
Crafted reusable UI elements (e.g., TaskCard, NavItem)

Followed atomic design principles for maintainability

Designed with flexibility to allow component expansion

2. State Management
Centralized logic using Redux Toolkit

tasksSlice → Stores and manages task states

activitiesSlice → Logs user interactions

Leveraged localStorage for state persistence

Added real-time updates for task shifts

3. Auth Flow
Built with Firebase Authentication

Used a custom AuthContext to manage user sessions and access control

4. UI/UX Design
Tailwind CSS for rapid styling

Drag-and-drop actions to enhance usability

Timeline UI for tracking user actions

🚀 Getting Started
Prerequisites
Node.js (v16 or newer)

A Firebase project (create one here)

🔧 Installation Steps
Clone the repository

bash
Copy
Edit
git clone https://github.com/ayushishr/Creative-Upaay
Install dependencies

bash
Copy
Edit
cd dashboard-creative-upaay
npm install
Setup environment variables
Create a .env file in the root directory with your Firebase config:

env
Copy
Edit
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
VITE_FIREBASE_APP_ID=your_app_id
Run the development server

bash
Copy
Edit
npm run dev
