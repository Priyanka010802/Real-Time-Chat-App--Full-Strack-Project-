# 🚀 Real-time MERN Chat App

A premium, state-of-the-art Real-Time Chat Application built with the MERN stack (MongoDB, Express, React, Node.js). Featuring a WhatsApp-inspired dark UI, real-time messaging, and **GitHub Information Integration**.

## ✨ Key Features

- **Real-Time Communication**: Powered by Socket.io for instant messaging.
- **WhatsApp Inspired UI**: Sleek, modern dark mode design using Tailwind CSS.
- **GitHub Integration**: View any user's GitHub profile, repositories, and stats directly from their avatar.
- **Authentication**: Secure JWT-based login and registration.
- **Online Status**: Real-time indicators of who is currently online.
- **Responsive Design**: Fully responsive and optimized for all devices.

## 🛠️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS, Lucide React, Framer Motion.
- **Backend**: Node.js, Express.js.
- **Database**: MongoDB (Mongoose).
- **Socket**: Socket.io for real-time events.

## 🚀 Getting Started

### Prerequisites
- Node.js installed
- MongoDB (Local or Atlas)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Priyanka010802/Real-Time-Chat-App--Full-Strack-Project-.git
   cd Real-Time-Chat-App--Full-Strack-Project-
   ```

2. **Install Dependencies**
   ```bash
   npm run install-all
   ```

3. **Environment Setup**
   Create a `.env` file in the `server` directory:
   ```env
   PORT=5001
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   FRONTEND_URL=http://localhost:5173
   ```

4. **Run the Application**
   ```bash
   npm run dev
   ```

## 🌐 Deployment Guide (Direct & Deploy)

To deploy this application live:

### 1. Frontend (Vercel/Netlify)
- Connect your GitHub repository to **Vercel**.
- Set the root directory to `client`.
- Add environment variables (API URL).
- Deploy!

### 2. Backend (Render/Railway)
- Connect your GitHub repository to **Render**.
- Select "Web Service".
- Set Build Command: `npm install`
- Set Start Command: `node server/index.js`
- Add environment variables (MONGODB_URI, JWT_SECRET, etc.).

### 3. Automatic Deployment (GitHub Actions)
The project includes a GitHub Workflow in `.github/workflows/` that can be configured to auto-deploy to your chosen platform on every push to `main`.

## 📂 Project Structure

```text
RealChatApp/
├── client/           # React Frontend
│   ├── src/
│   │   ├── components/ # Reusable UI components
│   │   ├── context/    # Auth & Socket contexts
│   │   └── pages/      # Application pages
├── server/           # Node.js Backend
│   ├── models/       # Mongoose Schemas
│   ├── routes/       # API Routes
│   └── index.js      # Server Entry Point
```

## 👤 Author

**Priyanka**
- GitHub: [@Priyanka010802](https://github.com/Priyanka010802)

---
*Created with ❤️ by Priyanka*
