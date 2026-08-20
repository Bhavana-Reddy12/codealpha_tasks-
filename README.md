# Project Overview

Connectly is a professional frontend-only social media platform designed for users to connect, share, and discover content. This project serves as a college demonstration of a fully functional social media application built using HTML5, CSS3, Vanilla JavaScript, and Bootstrap 5.

## Features

- **Landing Page**: Engaging landing page with a hero section and feature cards.
- **User Registration**: Users can register with validation for required fields and duplicate checks.
- **User Login**: Secure login functionality with error handling for incorrect credentials.
- **User Feed**: Dynamic feed displaying posts with options to like, comment, and delete.
- **Profile Management**: Users can view and edit their profiles, follow/unfollow others.
- **Search Functionality**: Search for users by name or username with dynamic results.
- **Notifications**: Real-time notifications for interactions like follows, likes, and comments.
- **Dark/Light Mode**: Theme toggle that persists across sessions.
- **Responsive Design**: Fully responsive layout for various devices.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Bootstrap 5
- Bootstrap Icons
- Browser localStorage

## Folder Structure

```
connectly
├── index.html
├── login.html
├── register.html
├── feed.html
├── profile.html
├── edit-profile.html
├── search.html
├── notifications.html
├── css
│   └── style.css
├── js
│   ├── app.js
│   ├── auth.js
│   ├── feed.js
│   ├── posts.js
│   ├── profile.js
│   ├── search.js
│   └── notifications.js
└── README.md
```

## How to Run

1. Clone the repository or download the project files.
2. Open `index.html` in a web browser.
3. Use the application by registering a new account or logging in with demo accounts.

## Demo Accounts

- **Username**: alexjohnson / **Password**: password123
- **Username**: sarahwilliams / **Password**: password123
- **Username**: rahulsharma / **Password**: password123
- **Username**: priyapatel / **Password**: password123

## localStorage Explanation

The application uses localStorage to persist user data, posts, and notifications. This allows the application to maintain state across page refreshes and browser sessions.

## Screenshots

*Screenshots will be added here.*

## Future Improvements

- Implement a backend for user authentication and data storage.
- Enhance the UI with more interactive elements.
- Add real-time chat functionality.

## Production Architecture Note

This project is a demonstration and does not implement production-level security for authentication. It is intended for educational purposes only.