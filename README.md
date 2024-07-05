
# Melos Music

Welcome to Melos Music! This project is a web application that allows users to explore and listen to music. The application is divided into two main parts: the frontend and the backend.

## Table of Contents

- [Melos Music](#melos-music)
  - [Table of Contents](#table-of-contents)
  - [Overview](#overview)
  - [Frontend](#frontend)
    - [Dependencies](#dependencies)
    - [Scripts](#scripts)
  - [Backend](#backend)
    - [Dependencies](#dependencies-1)
    - [Scripts](#scripts-1)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Running the Application](#running-the-application)
  - [Contributing](#contributing)
  - [License](#license)

## Overview

Melos Music is a full-stack web application that includes a frontend built with React and a backend powered by Express and MongoDB. The application allows users to register, log in, and enjoy a seamless music streaming experience.

## Frontend

The frontend is built with React and includes several dependencies to provide a rich user experience.

### Dependencies

The main dependencies used in the frontend are:

- React
- React Router DOM
- Tailwind CSS
- Cloudinary
- Howler

For a complete list of dependencies, refer to the package.json file in the frontend folder.

### Scripts

The available scripts for the frontend are:

- `start`: Starts the development server.
- `build`: Builds the application for production.
- `test`: Runs the test suite.
- `eject`: Ejects the configuration (use with caution).

## Backend

The backend is built with Express and MongoDB, and it includes several dependencies to handle authentication, data storage, and security.

### Dependencies

The main dependencies used in the backend are:

- Express
- Mongoose
- Passport
- JSON Web Token (JWT)
- Bcrypt
- Cors

For a complete list of dependencies, refer to the \`package.json\` file in the \`backend\` folder.

### Scripts

The available script for the backend is:

- `test`: Runs the test suite.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js
- npm
- MongoDB

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ipranavarora/melos-music.git
   cd melos-music
   ```

2. Install dependencies for the frontend and backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

### Running the Application

1. Start the backend server:

   ```bash
   cd backend
   npm start
   ```

2. Start the frontend development server:

   ```bash
   cd frontend
   npm start
   ```

3. Open your browser and navigate to `http://localhost:3000`.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the ISC License.
