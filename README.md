# WebSocket Chat App

A real-time chat application using **WebSockets**, **JWT authentication**, **SQLite** for message and credential storage, and **bcrypt** for encryption. Users can upload avatars to personalize their profiles.

## [https://cipherconnect.onrender.com](https://cipherconnect.onrender.com)

## Features

- **Real-time messaging** with WebSockets
- **User authentication** using JWT
- **SQLite database** for storing messages and user credentials
- **Bcrypt hashing** for password and message encryption
- **Avatar uploads** with file validation

## Technologies Used

- **Backend:** Node.js, Express, WebSockets
- **Database:** SQLite
- **Authentication:** JWT (JSON Web Tokens)
- **Encryption:** Bcrypt
- **Frontend:** HTML, CSS, JavaScript

## Security

- **Passwords** are hashed with **bcrypt** before storage.
- **Messages** are also encrypted before saving.
- **JWT authentication** protects user sessions.
- **Avatar uploads** are validated for size and type.


