# LionPortal - Premium Auth System

A modern, secure login and registration system built with Node.js, Express, and SQLite.

## Features
- **Visuals**: stunning Glassmorphism UI with animated background blobs.
- **Backend**: robust Express.js server with SQL database integration.
- **Security**: industry-standard password hashing using `bcryptjs`.
- **Database**: SQLite for lightweight, reliable local data storage.

## Getting Started
1. **Ensure Node.js is installed**.
2. **Run the server**:
   ```bash
   node server.js
   ```
3. **Open the app**:
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser.

## Functionality
- **Sign Up**: Create a new account with Name, Email, and Password. The password will be hashed and stored in `database.db`.
- **Sign In**: Login with your credentials. The system checks the database to verify if you are registered and if the password matches.
- **Session**: On successful login, user details are saved to `localStorage` for persistence.
