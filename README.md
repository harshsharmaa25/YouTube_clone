# YouTube_clone
 
# YouTube Clone (MERN Stack)

This project is a YouTube Clone built using the **MERN Stack** (MongoDB, Express, React, Node.js). It allows users to upload videos, watch videos, and interact with the content, similar to YouTube.

## Table of Contents
- [Project Setup](#project-setup)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [Features](#features)
- [Technologies](#technologies)
- [Folder Structure](#folder-structure)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Project Setup

### Backend Setup

1. **Clone the repository:**
   ```bash
    git clone https://github.com/harshsharmaa25/YouTube_clone.git
    cd YouTube_Clone



  *Clone the repository*
  
    ### git clone https://github.com/harshsharmaa25/YouTube_clone.git
    
   cd Backend
   cd ./server
   npm install
   npm start

  2. **Frontend Setup**

    cd Frontend
    cd ./client
    npm install
3. **Running the Application**

    - Start the backend server
        npm start

    - Start the frontend application
        npm run dev



    /youtube-clone
  /backend
    /models           # MongoDB models (e.g., User, Video, Comment) 🧳
    /routes           # API routes (e.g., authRoutes.js, videoRoutes.js) 📍
    /controllers      # Business logic for API routes 🧠
    /middlewares      # Middleware (e.g., authentication check) 🛡️
    /config           # Configuration files (e.g., database connection) ⚙️
    server.js         # Backend entry point 🌟
    .env              # Environment variables 🌳
  /frontend
    /src
      /components     # React components (e.g., Navbar, VideoPlayer) 🧩
      /pages          # Pages (e.g., HomePage, UploadPage) 📃
      /services       # API services for backend interaction 🖧
      /App.js         # Main React app file 🖥️
      /index.js       # Entry point for React 💻
    package.json      # Frontend dependencies 📜
    .env              # Frontend environment variables 🌐
  package.json        # Root package.json for managing dependencies 📦
  README.md           # Project documentation 📖

**Environment Variables Create a .env file in the backend directory with the following variables:**
MongoDB_URL="mongodb://localhost:27017/YoutubeClone"  # MongoDB connection string 🌱
Jwt_secret_key="MySecretKey123"                        # JWT Secret Key 🔐
PORT=3000                                              # Port number for the backend server 🌐

