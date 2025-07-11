# 🎉 Event Manager Application

A simple event management application built with Node.js, Express, and Handlebars templating.

## 🚀 Getting Started

### Prerequisites
- **Node.js** (v12 or higher)
- **npm** (Node Package Manager)

### Installation & Setup

1. **Clone and navigate to the project directory**
   ```bash
   cd sample-master/aer-sample-master
   ```

2. **Open two separate terminal sessions:**

   **Terminal 1 - Internal Service (Backend):**
   ```bash
   cd internal
   npm install
   node server.js
   ```
   
   **Terminal 2 - External Service (Frontend):**
   ```bash
   cd external
   npm install
   npm start
   ```

3. **Access the application**
   - Open your browser and navigate to: **http://localhost:8080**

## 📖 Application Overview

This sample application demonstrates a **microservices architecture** using Node.js and Express:

- **🔧 Internal Service (Port 8082)**: Backend API that handles REST requests and returns mock event data
- **🌐 External Service (Port 8080)**: Frontend web server that renders HTML templates using data from the internal service
- **🎨 Handlebars Templates**: Dynamic HTML rendering with styled components

## 🧪 Running Tests

```bash
cd external
npm test
```

## 📁 Project Structure

```
sample-master/
├── external/                 # Frontend service
│   ├── views/
│   │   ├── layouts/
│   │   │   └── default.hbs  # Main layout template
│   │   ├── home.hbs         # Events list template
│   │   └── error_message.hbs # Error page template
│   ├── test/
│   ├── server.js            # Frontend server
│   └── package.json
├── internal/                 # Backend service
│   ├── test/
│   ├── server.js            # Backend API
│   └── package.json
└── README.md
```

---

**Happy Coding! 🚀**
