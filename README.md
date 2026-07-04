# 💬 Real-Time Chat App (ANID-Chat)

ANID-Chat a modern real-time chat application built with the **MERN Stack** and **Socket.IO**. Users can sign up, log in securely, chat instantly with other users, upload profile pictures, and see online/offline status in real time.

---

## 🚀 Features

- 🔐 User Authentication (JWT)
- 👤 User Registration & Login
- 💬 Real-Time Messaging
- 🟢 Online / Offline User Status
- 🖼️ Image Sharing in Chat
- 📷 Profile Image Upload
- ☁️ Image Storage with ImageKit
- 📱 Responsive UI
- 🔒 Protected Routes
- ⚡ Instant Message Delivery using Socket.IO
---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Axios
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Bcrypt
- Socket.IO
- ImageKit (Image Upload & Storage)

---

## 📂 Project Structure

```
chat-app/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── lib/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/chat-app.git
```

```bash
cd chat-app
```

---

### Install Dependencies

#### Backend

```bash
cd server
npm install
```

#### Frontend

```bash
cd ../client
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the **server** folder.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint

CLIENT_URL=http://localhost:5173
```

---

## ▶️ Run the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm run dev
```

---

## 🌐 Live Demo

Frontend:
```
https://your-frontend-url.vercel.app
```

Backend:
```
https://your-backend-url.onrender.com
```

## 📡 API Endpoints

### Authentication

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | /api/auth/signup | Register User |
| POST | /api/auth/login | Login User |
| GET | /api/auth/check | Check Authentication |

### Messages

| Method | Endpoint | Description |
|---------|----------|-------------|
| GET | /api/messages/users | Get Users |
| GET | /api/messages/:id | Get Messages |
| POST | /api/messages/send/:id | Send Message |

---

## 🔄 Socket.IO Events

### Client → Server

- userConnected
- sendMessage

### Server → Client

- receiveMessage
- getOnlineUsers

---

## 🔒 Authentication

JWT-based authentication is implemented. Protected routes require a valid token stored in cookies.

---

## 🎯 Future Improvements

- ✅ Message Seen Status
- ✅ Voice Messages
- ✅ Video Calling
- ✅ Group Chat
- ✅ Push Notifications

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Create a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Akash**

---

⭐ If you like this project, don't forget to give it a star!
