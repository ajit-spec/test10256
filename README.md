# MEAN Stack Application

## Overview

This is a MEAN stack application, which uses MongoDB, Express.js, Angular, and Node.js to create a full-stack web application.

## Technologies

- **MongoDB**: NoSQL database used to store application data
- **Express.js**: Web application framework for Node.js
- **Angular**: Front-end web application framework
- **Node.js**: JavaScript runtime environment

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running
- Angular CLI installed (`npm install -g @angular/cli`)

### Installation

1. Clone the repository

   ```
   git clone https://github.com/yourusername/mean-app.git
   cd mean-app
   ```

2. Install server dependencies

   ```
   npm install
   ```

3. Install client dependencies

   ```
   cd client
   npm install
   cd ..
   ```

4. Configure environment variables
   - Create a `.env` file in the root directory
   - Add necessary environment variables (MongoDB URI, JWT secret, etc.)

### Running the Application

1. Start the server

   ```
   npm start
   ```

2. Start the Angular client

   ```
   cd client
   ng serve
   ```

3. Open your browser and navigate to `http://localhost:4200`

## Project Structure
