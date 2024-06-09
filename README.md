# Library Management System

A library management system built using the MERN stack (MongoDB, Express, React, Node.js).

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- View a list of all books in the library
- Add new books to the library

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Backend Setup

1. Clone the repository:
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
   
2.   Install backend dependencies:

cd backend
npm install

3.Set up environment variables:
Create a .env file in the backend directory and add your MongoDB connection string:



MONGO_URI=your_mongo_connection_string

4.Start the backend server:

npm run server


###Frontend Setup
Navigate to the client directory and install frontend dependencies:

cd ../client
npm install

Start the React development server:

npm start

Example Book Object
json
{
  "title": "Book Title",
  "author": "Author Name",
  "publishedDate": "2022-01-01",
  "genre": "Genre",
  "available": true
}

project structure:
library-management-system/
├── backend/
│   ├── config/
│   ├── controllers/
│   │   └── bookController.js
│   ├── models/
│   │   └── Book.js
│   ├── routes/
│   │   └── bookRoutes.js
│   ├── .env
│   ├── server.js
│   └── package.json
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   └── BookList.js
│   │   ├── services/
│   │   │   └── bookService.js
│   │   ├── App.js
│   │   └── index.js
│   ├── .env
│   └── package.json
└── README.md

