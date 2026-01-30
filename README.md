# 🤫 Secrets App

A small web app where users can sign in and anonymously share their secrets.

Built as a learning project using Express, EJS, Passport authentication, and PostgreSQL.

## ✨ Features
- Google Sign-In (OAuth 2.0)
- Local authentication with email and password
- Password hashing with bcrypt (salted hashes)
- Secure session-based authentication
- Post and update a personal secret
- Secrets stored in PostgreSQL
- Server-rendered UI with EJS

## 🛠 Tech Stack
- Node.js & Express
- EJS templates
- Passport.js (Google OAuth & Local Strategy)
- PostgreSQL
- bcrypt

## 🚀 Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Set environment variables
Create a `.env` file in the root directory:

```env
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
SESSION_SECRET=your_session_secret
```

### 3. Start the server
```bash
npm start
```

### 4. Open the app
```
http://localhost:3000
```

## 🔐 Authentication
Users can authenticate in two ways:
- Google OAuth 2.0
- Email and password login using bcrypt for secure password hashing with salt

Once authenticated, users can submit or update their own secret.
