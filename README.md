# Real-Time Chat App

A full-stack real-time chat application built using the MERN stack. It supports secure user authentication, one-to-one messaging, and real-time communication using Socket.IO.

## Features

- User authentication with JWT
- Real-time messaging using Socket.IO
- Online/offline user status
- Responsive user interface
- Image sharing support
- Secure backend APIs
- MongoDB database integration

## Tech Stack

### Frontend
- React
- Tailwind CSS
- DaisyUI
- Zustand
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT
- Cloudinary

## Installation

### Clone the repository

```bash
git clone <repository-url>
cd Real-time-Chat-App
```

### Install dependencies

Backend:

```bash
cd backend
npm install
```

Frontend:

```bash
cd ../frontend
npm install
```

## Environment Variables

Create a `.env` file inside the `backend` directory.

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

## Running the Application

Start the backend:

```bash
cd backend
npm run dev
```

Start the frontend:

```bash
cd frontend
npm run dev
```

## Project Structure

```
Real-time-Chat-App/
├── backend/
├── frontend/
├── package.json
└── README.md
```

