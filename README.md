# 🚀 Real-Time Chat Application

A full-featured, real-time messaging application built from the ground up with **Node.js**, **Express**, **WebSockets**, and **MongoDB**.  
This project showcases a complete user authentication system, admin privileges, persistent storage, and a dynamic, themeable front-end.

---

## ✨ Key Features

- **Real-Time Messaging**: Instant message and image delivery using WebSockets.  
- **Secure User Authentication**: Full signup, login, and session management using JWT and password hashing (`bcrypt`).  
- **Admin Role & Privileges**: Admins can delete any message and clear the entire chat history.  
- **Dynamic User Profiles**: View user profiles, edit your own information, and upload a custom profile picture.  
- **Image Messaging**: Share images in the chat, stored and retrieved from MongoDB.  
- **Persistent History**: Messages are saved to MongoDB Atlas and loaded on reconnect.  
- **Live Validation**: Real-time username and email availability checks on signup.  
- **Dual Theme**: Sleek UI with persistent **Dark** and **Light** mode options.  
- **Multilingual Support**: Profile page supports **English**, **Hindi**, and **Punjabi** with client-side translations.  

---

## 🛠️ Tech Stack

**Backend**: Node.js, Express, WebSockets  
**Frontend**: HTML, CSS, JavaScript  
**Database**: MongoDB Atlas  

---

## 📸 Screenshots

- Login page for user authentication  
- Signup page with real-time validation  
- Main chat window (text & image messaging)  
- Profile page with **Dark Mode**  

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites
- Node.js and npm installed  
- A free [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) account and connection string  

### Installation & Setup

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
Navigate to the project directory

bash
Copy code
cd your-repo-name
Install dependencies

bash
Copy code
npm install
Set up environment variables

Create a .env file in the root directory.

Copy content from .env.example.

Add your MongoDB URI and JWT secret.

Example .env file:

ini
Copy code
MONGO_URI=your_mongodb_connection_string_here
JWT_SECRET=your_super_strong_and_random_jwt_secret_here
Run the Application
bash
Copy code
node server.js
Visit: http://localhost:3000

📁 Folder Structure
java
.
├── middlewares/
│   └── authMiddleware.js
├── models/
│   ├── message.js
│   └── user.js
├── public/
│   ├── auth.js
│   ├── index.html
│   ├── login.html
│   ├── profile.html
│   ├── script.js
│   └── ... (CSS and other assets)
├── routes/
│   ├── auth.js
│   └── user.js
├── .env
├── .gitignore
├── package.json
└── server.js
📄 License
Distributed under the MIT License.
See LICENSE for details.

👤 Contact
Manthan Garg
📧 your-Manthan11016@gmail.com

🔗 Project Link: https://github.com/Manthan1104/Chat

yaml
copy the code
