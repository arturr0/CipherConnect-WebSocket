# WebSocket Chat App

![Chat App Preview](https://cdn.glitch.global/d003696d-9cab-4d96-baa5-bb1fa981a660/cipherconnect.png?v=1735931631075)
A real-time chat application using **WebSockets**, **JWT authentication**, **SQLite** for message and credential storage, and **bcrypt** for encryption. Users can upload avatars to personalize their profiles.

## <a href="https://cipherconnect.onrender.com" target="_blank">https://cipherconnect.onrender.com</a>

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


