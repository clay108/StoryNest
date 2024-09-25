# BlogSphere

A full-stack blogging platform where users can create, update, delete, and view blog posts with images and text using the MERN (MongoDB, Express, React, Node.js) stack. This project enables users to publish blogs with images, view other users' blogs, and manage their own posts.

## Features
- **User Authentication**: Users can register and log in to create and manage their blog posts.
- **Blog Creation**: Users can write blogs with an image and text content.
- **Update and Delete Blogs**: Authors can edit or delete their own blogs.
- **Responsive Design**: The application is mobile-friendly and adapts to various screen sizes.
- **MongoDB Storage**: Blogs are stored in MongoDB, including image URLs and text data.
- **REST API**: The backend exposes a RESTful API for managing blogs, users, and authentication.

## Tech Stack
- **Frontend**: React.js
  - Axios for HTTP requests
  - React Router for page navigation
  - Styled Components / CSS Modules for styling

- **Backend**: Node.js, Express.js
  - RESTful API for managing blog data and user authentication
  - Multer for handling image uploads
  - JWT (JSON Web Tokens) for authentication

- **Database**: MongoDB with Mongoose
  - Storing user data and blog post information (title, image URL, blog details, etc.)

- **Authentication**: JWT-based authentication for user login and registration.

## Installation

### Prerequisites
- Node.js (v14+)
- MongoDB (local or cloud e.g., MongoDB Atlas)
- NPM (or Yarn)

### How to run this project on your machine
- 1.clone the repository
- 2.open the VS code and split the terminal one for the backend and other for frontend
- 3.make a config folder in the backend and .env file in this folder
- 4.install modules for both backend and frontend using 
```bash
   npm i
```
-5.run the following command on both terminal
```bash
   npm run dev
```
### ScreenShots
-1.DashBoard
![Dashboard](https://github.com/clay108/BlogApp/blob/main/dashboard.png)
-2.Home Page
![Home](https://github.com/clay108/BlogApp/blob/main/Home%20page.png)
-3.Upload Post
![Upload](https://github.com/clay108/BlogApp/blob/main/upload%20post.png)


