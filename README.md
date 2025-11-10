# Spotify Clone

A full-stack music streaming application that replicates core Spotify features, allowing users to discover, play, and manage music with real-time social features.

## About

This Spotify Clone is a modern web application that provides a music streaming experience similar to Spotify. It includes features such as music playback, album management, user authentication, real-time chat, and social interactions. The application is built with a separation of concerns between frontend and backend, providing a scalable and maintainable architecture.

## Tech Stack

### Frontend
- **React** - UI library for building interactive user interfaces
- **TypeScript** - Type-safe JavaScript for better code quality and developer experience
- **Vite** - Fast build tool and development server
- **React Router DOM** - Client-side routing for navigation
- **Tailwind CSS** - Utility-first CSS framework for styling
- **Axios** - HTTP client for API requests
- **Zustand** - Lightweight state management library
- **Clerk** - Authentication and user management
- **Socket.io Client** - Real-time communication for chat and live features
- **Lucide React** - Icon library
- **React Hot Toast** - Toast notifications
- **Radix UI** - Accessible UI component primitives

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database for storing application data
- **Mongoose** - MongoDB object modeling tool
- **Socket.io** - Real-time bidirectional event-based communication
- **Cloudinary** - Cloud-based image and media management
- **JWT** - JSON Web Tokens for authentication
- **bcrypt** - Password hashing

### Development Tools
- **ESLint** - Code linting and quality assurance
- **TypeScript** - Static type checking
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing

## Project Structure

```
Spotify-Clone/
├── backend/          # Node.js/Express backend
│   ├── src/
│   │   ├── controller/   # Request handlers
│   │   ├── models/       # Database models
│   │   ├── routes/       # API routes
│   │   ├── middleware/   # Custom middleware
│   │   └── lib/          # Utilities (db, socket, cloudinary)
│   └── package.json
├── frontend/         # React/TypeScript frontend
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── pages/        # Page components
│   │   ├── stores/       # State management
│   │   ├── providers/    # Context providers
│   │   ├── layout/       # Layout components
│   │   └── lib/          # Utilities
│   └── package.json
└── README.md
```

## Features

- User authentication and authorization
- Music playback with audio controls
- Album and song management
- Real-time chat functionality
- Social features (friends activity)
- Admin dashboard for content management
- Responsive design
- Search and discovery

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- MongoDB database
- Cloudinary account (for media storage)
- Clerk account (for authentication)

### Installation

1. Clone the repository
2. Install dependencies for both frontend and backend:
   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

3. Configure environment variables in both backend and frontend
4. Start the development servers:
   ```bash
   # Backend
   cd backend && npm start
   
   # Frontend
   cd frontend && npm run dev
   ```

## License

This project is for educational purposes.

