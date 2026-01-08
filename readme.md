#  Instagram Clone (MERN Stack)

A full-featured social media application inspired by Instagram. Built with the MERN stack (MongoDB, Express, React, Node.js). Users can sign up, post photos, like posts, comment, and follow others.

##  Features

-  User authentication (JWT-based)
-  Post creation with image uploads
-  Like and comment functionality
-  Follow / Unfollow users
-  Responsive UI with React
-  User profiles and feeds
-  user Explore
-  User Message and chatting with notification 
-  Search functionality

##  Tech Stack

### Frontend:
- React
- React Router
- Redux
- Tailwind CSS
- Axios
- Socket-io-client

### Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT (JSON Web Tokens)
- bcrypt-js (encrypting-password in hash)
- cors (allows backend to accept request from different domain)
- cookie-parser (Reads and parses cookies sent from the browser.)
- datauri (Converts files (like images) into base64 URLs for easy upload/transfer.)
- Multer (Handles file uploads (images, videos, etc.) in Node.js.)
- Cloudinary / Local storage (image hosting)
- sharp (High-performance image processing library (resize, compress, convert formats).)
- Nodemon (Automatically restarts your server when you change code.)

##  Project Structure

    /backend
    ├── controllers
    ├── models
    ├── routes
    ├── middleware
    |-- socket
    |-- utils
    └── server.js
    |-- .env
    /frontend
    |-- public
    ├── src
    ├── components
        |- ui
        |- *components_files
    ├── hooks
    |-- lib
    |-- redux
    └── App.js


##  Installation

1. **Clone the repository:**
```bash
git clone https://github.com/DevPatel1023/Link_Node.git
cd Link_Node

2. **Install backend dependencies:**
```bash
cd backend
npm install

3. **Install frontend dependencies:**
```bash
cd frontend
npm install

4. **configure Enviorement variables in backend .env file :**
```bash

PORT=8000
MONGO_URL=mongo_db_url_string
JWT_SECRET=jwt_secret_string
CLOUDINARY_NAME=cloud_name
CLOUDINARY_API_KEY=cloud_api_key
CLOUDINARY_API_SECRET=cloud_api_secret


5. **Run the developement server:**
```bash
# In backend/
npm run dev

# In frontend/
npm run dev

 Screenshots

 Author
    Dev Patel
