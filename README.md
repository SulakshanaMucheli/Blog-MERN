# Blog Post Application

A simple blog post application built with the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Demo](#demo)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Description

This project is a full-stack web application that allows users to view blog posts, create new posts, and view individual post details. It integrates MongoDB as the database, Express.js and Node.js for the backend server, and React.js for the frontend user interface.

## Features

- Display a list of blog posts with titles and excerpts.
- Allow users to click on a post to view the full content.
- Create new blog posts with a title and body.
- Responsive design to ensure compatibility across various devices.


## Technologies

- **MongoDB**: NoSQL database used to store blog post data.
- **Express.js**: Backend framework for handling API requests and routing.
- **React.js**: Frontend library for building user interfaces.
- **Node.js**: JavaScript runtime environment for executing server-side code.
- **Axios**: Promise-based HTTP client for making API requests.
- **React Router**: Declarative routing for React applications.
- **CORS**: Middleware for enabling Cross-Origin Resource Sharing.

## Setup

To run this project locally, follow these steps:

### Prerequisites

- Node.js installed on your local machine.
- MongoDB server running locally or accessible via a MongoDB Atlas cluster.

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/blog-post-app.git
cd blog-post-app
```
-FRONTEND INSTALLATION
```bash
npx create-react-app client
npm install react-router-dom
npm install axios
```
-BACKEND INSTALLATION
```bash
npm install express
npm install mongoose
npm install cors
npm install dotenv
npm install nodemon --save-dev
```


## Usage

### Start the server
-Running on 5000 port

```bash
node server.js
```
### Start the client
```bash
npm start
```
## API EndPoints
  - **GET /api/posts**: Retrieves all blog posts.
  - **GET /api/posts/:id**: Retrieves a specific blog post identified by `:id`.
  - **POST /api/posts**: Creates a new blog post.
  - **DELETE /api/posts/:id**: Deletes a blog post identified by `:id`.


