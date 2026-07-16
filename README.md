# 💬 Real-Time Chat Application

A modern real-time chat application built with the MERN Stack that enables users to communicate instantly through one-to-one messaging. The application provides secure authentication, real-time communication using Socket.IO, profile management, image sharing, and a responsive user interface.

---

## 🚀 Features

- Secure user authentication (JWT)
- Real-time one-to-one messaging
- Online/offline user status
- Instant message delivery with Socket.IO
- Image sharing in chats
- User profile management
- Cloud image storage with Cloudinary
- Responsive UI for desktop and mobile
- Protected routes
- Persistent chat history

---

## 🛠 Tech Stack

### Frontend

- React.js
- Vite
- Tailwind CSS
- Axios
- React Router DOM
- Context API

### Backend

- Node.js
- Express.js
- Socket.IO
- JWT Authentication
- Multer

### Database

- MongoDB
- Mongoose

### Cloud Services

- Cloudinary

### Deployment

- Vercel (Frontend)
- Render (Backend)
- MongoDB Atlas

---

## 📂 Project Structure

```
chat-application/
├── client/
├── server/
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/JeevaFsd-0/chatapp.git
```

### Install Dependencies

#### Client

```bash
cd client
npm install
```

#### Server

```bash
cd server
npm install
```

---

## 🔧 Environment Variables

Create a `.env` file inside the `server` folder.

```env
PORT=5000

MONGODB_URI=

JWT_SECRET=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=

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

## 📸 Screenshots

### Login Page

<img width="1919" height="899" alt="image" src="https://github.com/user-attachments/assets/7f7f1ae0-c23a-4d68-96b8-8674b032519f" />

### Signup Page

<img width="1919" height="897" alt="image" src="https://github.com/user-attachments/assets/5f055e1d-b3eb-4e58-baf1-7314982235c7" />

### Chat Dashboard

<img width="1918" height="889" alt="image" src="https://github.com/user-attachments/assets/8c91a225-7beb-4b36-be19-35da126e465e" />

### User Profile

<img width="1919" height="902" alt="image" src="https://github.com/user-attachments/assets/0cf42614-6b99-4107-b699-a4ac0ff8a7e2" />

### Mobile View

<img width="784" height="825" alt="image" src="https://github.com/user-attachments/assets/ed6f3fb3-4a0a-45e4-a714-8ce8f6f0bd91" />

---

## 🌐 Live Demo

**Frontend**

https://chatapp-kappa-ashen.vercel.app/login

**Backend**

https://chatapp-backend-mern15.vercel.app/

---

## 📡 API Endpoints

### Authentication

```
POST /api/auth/register
POST /api/auth/login
GET  /api/auth/profile
PUT  /api/auth/update-profile
```

### Messages

```
GET  /api/messages/:receiverId
POST /api/messages/send
```

---

## 🔒 Authentication

The application uses JWT-based authentication to secure protected routes and ensure authorized access.

---

## ⚡ Real-Time Features

- Instant messaging
- Online/offline user status
- Live message updates
- Real-time image sharing
- Automatic chat refresh
- Socket.IO integration

---

## 📈 Future Enhancements

- Group chat
- Voice messages
- Video calling
- Message reactions
- Read receipts
- Typing indicators
- Push notifications
- Message search
- Dark mode
- End-to-end encryption

---

## 👨‍💻 Author

**Jeevanantham P**

- GitHub: https://github.com/JeevaFsd-0
- LinkedIn: https://www.linkedin.com/in/your-linkedin-profile

---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
