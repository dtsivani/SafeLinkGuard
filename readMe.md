# SafeLinkGuard

This project is built using Node.js (v18 LTS) for the backend and a React Native application created with Expo for the frontend. The backend server was generated using `express-typescript-generator`.

## Environment Setup

### Prerequisites

1. **Node.js**: Ensure you have Node.js v18 (LTS) installed. You can download it from [Node.js official website](https://nodejs.org/).
2. **Expo CLI**: Install Expo CLI globally using npm:
   ```bash
   npm install -g expo-cli
   ```
3. **Dependencies**: Install project dependencies for both backend and frontend.

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the backend directory and configure the required environment variables.

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the Expo development server:
   ```bash
   expo start
   ```

## Running the Application Locally

### Start the Backend Server

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Start the server:
   ```bash
   npm run dev
   ```

### Start the Frontend Application

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Start the Expo development server:
   ```bash
   npx expo run:android
   ```
3. Use the Expo Go app on your mobile device or an emulator to scan the QR code and run the application.

## Notes

- Ensure both backend and frontend are running simultaneously for the application to function correctly.
- For any issues, check the logs in the terminal for debugging.
- Update the `.env` file with appropriate configurations for your local environment.


