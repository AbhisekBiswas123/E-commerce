# E-commerce MERN Stack Application

This project is a full-stack e-commerce platform built using the MERN stack (MongoDB, Express, React, Node.js). It includes secure admin authentication using JWT and features for adding and removing products from the database.

## Features

- Admin authentication using JWT (token stored in localStorage).
- Add and delete products from the MongoDB database.
- Image Uploads: Used Multer for uploading and saving images.
- Frontend built with React and deployed on Netlify.
- Backend built with Node.js, Express, and connected to MongoDB, deployed on Render.
  
## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2. Setting up the Backend

Navigate to the `backend` directory:

```bash
cd backend
```

#### Install dependencies:

```bash
npm install
```

#### Configure environment variables:

Create a `.env` file in the `backend` folder and add the following (replace values as needed):

```
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
PORT=3000
```

#### Start the backend server:

For development (with auto-restart on file changes):

```bash
nodemon index.js
```

Alternatively, to run without Nodemon:

```bash
node index.js
```

### 3. Setting up the Frontend

Navigate to the `frontend` directory:

```bash
cd ../frontend
```

#### Install dependencies:

```bash
npm install
```

#### Start the frontend development server:

```bash
npm run dev
```

This will start the React frontend 

## Running the Application

1. Ensure your **MongoDB** instance is running.
2. Start the **backend** server (`nodemon index.js`).
3. Start the **frontend** server (`npm run dev`).


## Deployment

- **Frontend**: Deployed on Netlify.
- **Backend**: Deployed on Render.
