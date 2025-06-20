<p align='center'><img src="./Frontend/src/assets/RideNowLogo.png" alt="Logo Image" center height="60" weight="60" /> <h1>RideNow - Ride Booking System using MERN stack and Google Maps API.<h1/> <p/>

RideNow is a full-stack ride-booking application inspired by Uber, built with a React frontend and a Node.js/Express backend. It allows users to book rides, captains (drivers) to accept rides, and features real-time updates using Socket.IO and Google Maps integration.

## Features

- User and Captain (Driver) registration & login
- Google Authentication for Users
- Real-time ride requests and confirmations via Socket.IO
- Google Maps integration for location, directions, and suggestions
- Real time Route Navigation using Google Maps API
- Real time distance and time updates
- Fare calculation based on distance and time
- OTP-based ride start confirmation
- Live tracking of rides for both users and captains
- Responsive, modern UI with Tailwind CSS

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, @react-google-maps/api, GSAP, Socket.IO Client, Axios, React Router, React Toastify
- **Backend:** Node.js, Express, MongoDB (Mongoose), Socket.IO, Google Maps APIs, JWT, bcrypt
- **Other:** ESLint, dotenv

## Getting Started

### Prerequisites

- Node.js (v18+ recommended)
- MongoDB instance (local or cloud)
- Google Maps API Key (Google Cloud)

### Backend Setup

1. **Install dependencies:**
   ```sh
   cd "./Backend"
   npm install

2. **Configure environment variables:**
Create a .env file in Backend/ with:
   ```sh
   DB_CONNECT=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   GOOGLE_MAPS_API_KEY=your_google_maps_api_key
   GOOGLE_CLIENT_ID=your_google_client_id
   GOOGLE_CLIENT_SECRET=your_google_client_secret

4. **Start Backend Server:**
   ```sh
   npx nodemon

### Frontend Setup

1. **Install dependencies:**
   ```sh
   cd './Frontend'
   npm install
   
2. **Configure environment variables:**
Create a .env file in Frontend/ with:

   ```sh
   VITE_BASE_URL=http://localhost:3000
   VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key

4. **Start Frontend dev server:**
   ```sh
   npm run dev

### Usage
Open http://localhost:5173 in your browser.
Register as a user or captain and start booking or accepting rides!
   
### License
This project is for educational purposes.

**Made with ❤️ by Mohammed Fawzaan**
