# 🔐 PassVault – Local Storage Credential Manager

PassVault – Local Storage is a frontend credential management web application built using **React.js** and **Tailwind CSS**. It enables users to securely store, view, and manage website credentials directly in the browser using **Local Storage**, eliminating the need for a backend or database.

---

# 🚀 Features

## 🌍 Frontend

- Built using React.js with a modern, responsive user interface
- Animated action icons for copy, edit, and delete operations
- Hover effects for improved user interaction
- Clickable website URLs for quick navigation
- Password visibility toggle
- Clean table-based credential management interface

---

## 💾 Local Storage

- Browser-based credential persistence
- No backend server required
- Data remains available across browser sessions
- Automatic synchronization with Local Storage

---

## 🔐 Credential Management

Supports complete CRUD operations:

- Create new credentials
- Read stored credentials
- Update existing credentials
- Delete saved credentials

---

## 🛡️ Security

- Controlled credential management through client-side CRUD workflows
- Local-only data storage (credentials are persisted locally and never sent over the network)
- Copy-to-clipboard functionality for quick access
- Password visibility toggle for secure viewing

---

## ✨ User Experience

- Copy username or password with a single click
- Responsive design for desktop and mobile devices
- Fast client-side operations without network requests
- Simple and intuitive interface

---

# 🛠️ Tech Stack

### Frontend & Styling
- **React 19** (Frontend library)
- **Tailwind CSS v4** (Utility-first CSS framework via `@tailwindcss/vite`)
- **Vite** (Build tool and development server)
- **Lordicon** (Animated interactive icons)
- **React-Toastify** (Toast notifications for copy, save, and delete feedback)
- **UUID** (Unique ID generation for credentials)

### Storage & Persistence
- **Browser Local Storage** (Client-side persistent storage)

---

# 📂 Project Structure

```text
PassVault-LocalStorage/
├── public/
│   ├── icons/            # Interactive icons (eye, eyecross, github, heart)
│   ├── favicon.png       # Site favicon image
│   └── vite.svg          # Vite logo
├── src/
│   ├── assets/           # React logo asset
│   ├── components/       # React components
│   │   ├── Footer.jsx    # Page footer
│   │   ├── Manager.jsx   # Core credential manager component
│   │   └── Navbar.jsx    # Page navigation bar
│   ├── App.css           # App styling
│   ├── App.jsx           # Main application shell
│   ├── index.css         # CSS Entrypoint (imports Tailwind CSS)
│   └── main.jsx          # React mount entrypoint
├── eslint.config.js      # ESLint linting configuration
├── index.html            # Main HTML wrapper (loads Lordicon scripts)
├── package.json          # Project scripts, dependencies, and configuration
├── tailwind.config.js    # Tailwind configuration file
├── vite.config.js        # Vite configuration with React and Tailwind plugins
└── README.md             # Project documentation
```

---

# ▶️ Getting Started

## Prerequisites

- **Node.js** (v18+ recommended)
- **npm** (comes packaged with Node.js)

---

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/pjha91275/IronVault.git PassVault-LocalStorage
   ```

2. **Navigate into the project directory**
   ```bash
   cd PassVault-LocalStorage
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Access the application**
   Open your browser and navigate to:
   ```
   http://localhost:5173
   ```
   *(or the local URL displayed in your terminal by Vite)*

---

# 🎯 Learning Outcomes

- Built a responsive React.js application.
- Practiced state management using React Hooks.
- Implemented CRUD functionality.
- Learned browser Local Storage APIs.
- Improved frontend component design and user interaction.

---

# 🚀 Future Enhancements

- MongoDB database integration
- User authentication
- Password encryption
- Cloud synchronization
- Search and filtering
- Category management

---

# 👨‍💻 Author

**Prince Jha**

Computer Engineering Student

Thakur College of Engineering and Technology (TCET)

---

# ✅ Project Status

- ✔ Completed
- ✔ Tested
- ✔ Frontend-only implementation
