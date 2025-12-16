# Mini Social Media App (MERN Stack)

A mini social media application built using the **MERN Stack** that allows users to connect, share posts, follow other users, like posts, and comment in real time.

---

## 🚀 Features

- 🔐 User Authentication (Register / Login)
- 👤 User Profiles
- ➕ Create & Delete Posts
- ❤️ Like & Unlike Posts
- 💬 Comment on Posts
- ➖ Delete Comments (Owner Only)
- 👥 Follow & Unfollow Users
- 📰 Personalized Feed (Posts from Followed Users)
- 📱 Responsive UI

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Axios
- React Router DOM
- Context API / Redux (if used)
- CSS / Tailwind / Bootstrap

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js

---

## 📂 Project Structure

mini-social-media-app/
│
├── client/ # React Frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ ├── services/
│ │ └── App.js
│ └── package.json
│
├── server/ # Node + Express Backend
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── middleware/
│ ├── config/
│ └── server.js
│
└── README.md
API Endpoints (Sample)
Auth

POST /api/auth/register – Register user

POST /api/auth/login – Login user

Users

PUT /api/users/follow/:id – Follow user

PUT /api/users/unfollow/:id – Unfollow user

Posts

POST /api/posts – Create post

DELETE /api/posts/:id – Delete post

PUT /api/posts/like/:id – Like/Unlike post

Comments

POST /api/posts/comment/:id – Add comment

DELETE /api/posts/comment/:id/:commentId – Delete comment

🧪 Future Improvements

Real-time chat using Socket.io

Notifications system

Image upload with Cloudinary

Dark mode

Search users & posts

yaml
Copy code
