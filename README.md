# Connectly - Mini Social Media Platform

## Project Overview
Connectly is a professional full-stack social media platform designed for users to connect, share, and discover content. The application allows users to create profiles, post updates, follow other users, and engage with content through likes and comments.

## Features
- User registration and login
- Secure authentication with JWT
- User profiles with editable information
- Create and manage posts with image uploads
- Like and comment on posts
- Follow and unfollow users
- Notifications for likes, comments, and follows
- Explore and search for users
- Responsive design for mobile and desktop

## Tech Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Authentication:** JWT, bcryptjs
- **File Uploads:** Multer
- **Security:** Helmet, express-rate-limit

## Architecture
The project is structured into two main parts: the backend and the frontend. The backend handles API requests, authentication, and database interactions, while the frontend provides a user-friendly interface for interaction.

```
connectly/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── utils/
│   ├── seed/
│   └── server.js
└── frontend/
    ├── css/
    ├── js/
    └── html/
```

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/connectly.git
   cd connectly
   ```

2. Set up the backend:
   - Navigate to the backend directory:
     ```
     cd backend
     ```
   - Install dependencies:
     ```
     npm install
     ```
   - Create a `.env` file based on `.env.example` and configure your environment variables.
   - Start the backend server:
     ```
     npm run dev
     ```

3. Set up the frontend:
   - Navigate to the frontend directory:
     ```
     cd ../frontend
     ```
   - Open `index.html` in your browser to access the application.

## MongoDB Setup
Ensure you have MongoDB installed and running. Update the connection string in the `.env` file to point to your MongoDB instance.

## Environment Variables
- `MONGODB_URI`: MongoDB connection string
- `JWT_SECRET`: Secret key for JWT authentication
- Other necessary environment variables as specified in `.env.example`

## Running the Backend
To run the backend server, navigate to the backend directory and use:
```
npm run dev
```

## Running the Frontend
Open the `index.html` file in your preferred web browser.

## API Documentation
Refer to the API routes defined in the backend for detailed documentation on endpoints and their usage.

## Demo Credentials
- **User 1:** 
  - Email: user1@example.com
  - Password: password123
- **User 2:** 
  - Email: user2@example.com
  - Password: password123

## Project Structure
The project is organized into a clear structure separating backend and frontend components, making it easy to navigate and maintain.

## Security
The application implements secure practices including password hashing, JWT authentication, and input validation to protect user data.

## Future Improvements
- Implement additional features such as direct messaging and user groups.
- Enhance the UI/UX for a more engaging experience.
- Optimize performance for larger user bases.

## Author
Developed by [Your Name] - [Your GitHub Profile Link]