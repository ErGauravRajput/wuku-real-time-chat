# 💬 Wuku – Real-Time Live Chat Application

**Wuku** is a modern, real-time chat application that allows users to communicate instantly through private messages. It’s designed for speed, simplicity, and seamless communication, making it ideal for both desktop and mobile users.

---

## 🧩 Key Features

- ✅ **Real-Time Messaging** using WebSockets (Socket.IO)
- ✅ **One-on-One Chats**
- ✅ **User Authentication** (JWT)
- ✅ **Message Seen / Delivered Indicators**
- ✅ **Online/Offline Status**
- ✅ **Typing Indicators**
- ✅ **Responsive UI** (Mobile + Desktop)
- ✅ **Emoji Support**
- ✅ **Push Notifications**
- ✅ **Various Themes**

---

## 🛠️ Tech Stack

| Layer       | Technology                    |
|-------------|-------------------------------|
| Frontend    | React.js, HTML, CSS |
| Styling     | CSS, Tailwind, DaisyUI |
| Backend     | Node.js, Express.js |
| Real-Time   | Socket.IO |
| Database    | MongoDB,Cloudnary  |
| Auth        | JWT Authentication |

---

## 📁 WUKU – Folder Structure

### **📦Frontend**
```
frontend/
├── node_modules/                  # Installed frontend dependencies
├── public/
│   ├── avatar.png                     # Default avatar image
│   └── chatlogo.png                   # Chat app logo
│
├── src/
│   ├── components/                   # Reusable UI components
│   │   ├── skeletons/                    # Skeleton loading components
│   │   │   ├── MessageSkeleton.jsx
│   │   │   ├── SidebarSkeleton.jsx
│   │   │   └── AuthImagePattern.jsx     # Pattern shown on auth screens
│   │   ├── ChatContainer.jsx            # Main chat area
│   │   ├── ChatHeader.jsx               # Header of chat window
│   │   ├── MessageInput.jsx            # Input field to send messages
│   │   ├── Navbar.jsx                   # Top navigation bar
│   │   ├── NoChatSelected.jsx          # Placeholder view when no chat selected
│   │   └── Sidebar.jsx                 # Sidebar showing user chats
│   │
│   ├── constants/
│   │   └── index.js                    # Static config and constants
│   │
│   ├── lib/
│   │   ├── axios.js                    # Axios instance setup (with baseURL & interceptors)
│   │   └── utils.js                    # Utility functions
│   │
│   ├── pages/                         # Page-level views
│   │   ├── HomePage.jsx               # Main page after login
│   │   ├── LoginPage.jsx              # Login screen
│   │   ├── ProfilePage.jsx            # User profile and settings
│   │   ├── SettingsPage.jsx           # General app settings
│   │   └── SignUpPage.jsx             # Sign up screen
│   │
│   ├── store/                         # Global state management (e.g. Zustand, Redux, etc.)
│
│   ├── App.jsx                        # App root component
│   ├── index.css                      # Global styles
│   └── main.jsx                       # Entry point (renders <App />)
│
├── index.html                        # HTML entry for Vite
├── package.json                      # Project metadata and scripts
├── package-lock.json                 # Locked package versions
├── postcss.config.js                 # PostCSS config (used by Tailwind)
├── tailwind.config.js                # TailwindCSS customization
├── vite.config.js                    # Vite bundler config
├── eslint.config.js                  # ESLint configuration
└── README.md                         # Documentation file

```

### **📦Backend**
```
backend/
├── node_modules/                 # Installed backend dependencies
├── src/
│   ├── controllers/              # Business logic for routes
│   │   ├── auth.controller.js        # Handles user login/register
│   │   └── message.controller.js     # Manages message-related logic
│   │
│   ├── lib/                     # Core utilities and 3rd-party setup
│   │   ├── cloudinary.js            # Cloudinary upload config (images/media)
│   │   ├── db.js                    # MongoDB connection setup
│   │   ├── socket.js                # Socket.IO real-time logic
│   │   └── utils.js                # Helper functions
│   │
│   ├── middleware/              # Express middleware
│   │   └── auth.middleware.js       # JWT or session-based auth checks
│   │
│   ├── models/                  # Mongoose models (MongoDB schemas)
│   │   ├── message.model.js         # Message schema
│   │   └── user.model.js            # User schema
│   │
│   ├── routes/                  # Express route definitions
│   │   ├── auth.route.js            # /api/auth (register/login)
│   │   └── message.route.js         # /api/messages (send/get)
│   │
│   ├── seeds/                   # DB seeding scripts
│   │   └── user.seed.js             # Seed dummy users
│   │
│   └── index.js                 # App entry point (express + socket server)
│
├── .env                         # Environment variables (PORT, DB_URI, etc.)
├── package.json                 # Backend project metadata and scripts
├── package-lock.json            # Locked versions of npm packages

```
## 📸 Screenshots

| Page | Screenshot |
|------|-----------|
| *Login Page* |![Screenshot 2025-05-10 141039](https://github.com/user-attachments/assets/c2b142ab-0178-4d9f-a30a-dd58e71cb8bd)|
| *Registration | ![Screenshot 2025-05-10 141202](https://github.com/user-attachments/assets/897998b0-8109-4e1a-b860-45a4702011f9)|
| *Chat Interface* | ![Screenshot 2025-05-10 140907](https://github.com/user-attachments/assets/a01fd210-ba54-4637-ae8a-017d325f74f1)|
| *Profile Page* | ![Screenshot 2025-05-10 141016](https://github.com/user-attachments/assets/56a7237e-b4d4-4b30-bc51-0bd18f76dc21)|
| *Theme Setting* | ![Screenshot 2025-05-10 140923](https://github.com/user-attachments/assets/1d127887-8829-43e2-8a9e-340940e861ab)|


