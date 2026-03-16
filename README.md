# Stream Africa Mialiko Kadi

A complete fullstack SaaS application structure.

## Project Structure

- **client/** (React Frontend)
  - **public/**
    - index.html
  - **src/**
    - components/
      - App.js
      - Header.js
      - Footer.js
      - EventForm.js
    - context/
      - AuthContext.js
      - LanguageContext.js
    - styles/
      - App.css
    - App.js
    - index.js
  - package.json
- **server/** (Express Backend)
  - **config/**
    - db.js
  - **controllers/**
    - authController.js
    - eventController.js
  - **models/**
    - User.js
    - Event.js
  - **routes/**
    - auth.js
    - events.js
  - middleware/
    - authMiddleware.js
  - .env
  - server.js
  - package.json

## Features

- Multi-language support
- User Authentication
- Event Creation
- QR Code Generation
- WhatsApp Sharing
- Public Invitation Pages

## Instructions

1. Navigate to the `client` directory.
2. Install the React dependencies: `npm install`
3. Navigate to the `server` directory.
4. Install the Express dependencies: `npm install`
5. Create a `.env` file in the server directory with the necessary environment variables.
6. Run the server and client.

---
This template provides a base structure. Make sure to implement functionality as needed!