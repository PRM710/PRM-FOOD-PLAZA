# Project Setup and Run Instructions

## Configuration

### Backend
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Navigate to the src directory:
   ```bash
   cd src
   ```
3. Install the required dependencies:
   ```bash
   npm install bcrypt mongoose dotenv
   ```
4. Create a `.env` file inside the `src` directory and add the following:
   ```env
   MONGO_URI=YOUR_MONGO_KEY
   JWT_SECRET=YOUR_SECRET_KEY
   ```

### Frontend
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install the required dependencies:
   ```bash
   npm install
   npm install react-router-dom
   ```

## How to Run

### Backend
1. Open a terminal and navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Start the server:
   ```bash
   node server
   ```

### Frontend
1. Open a new terminal and navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Start the frontend application:
   ```bash
   npm start
   ```

