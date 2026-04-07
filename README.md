A modern Portfolio Content Management System (CMS) built entirely with frontend technologies. 
It simulates a full-stack environment using IndexedDB as a client-side database, enabling content management, analytics, and portfolio preview — 
all inside the browser.

🚀 Features
🔐 Authentication System
    Role-based access:
    Admin → Full control
    Viewer → Read-only mode
    Secure password hashing (SHA-256)
Session management using sessionStorage
📊 Dashboard
    Overview of projects, blog posts, views, and drafts
    Recent activity table with quick actions
📂 Project Management
    Create, update, delete projects
    Fields:
    Title, category, description
    Tags, status
    Image upload
    Filter by status
✍️ Blog Management
    Add and manage blog posts
    Category, tags, status support
    Cover image upload
📈 Analytics
    Content statistics and insights
    Top-performing projects and posts
    Category-based breakdown
🎨 Theme Customization
    Multiple UI themes
    Customizable:
    Name
    Bio
    Font
    Layout
    Stored using IndexedDB
👁 Portfolio Preview
    Public portfolio rendering
    Category filters
    Dynamic content display
🔌 API Simulation
    REST-like structure:
    GET, POST, PUT, DELETE
    Backend logic implemented in JavaScript
🧠 Tech Stack
    HTML5
    CSS3
    JavaScript (ES6)
    IndexedDB (browser database)
    Web Crypto API
🔑 Demo Credentials
    Role	Username	Password
    Admin	admin	admin123
    Viewer	viewer	view123

💾 Data Storage
    Uses IndexedDB for persistent client-side storage
    No external backend required
    Data remains until browser storage is cleared
⚠️ Disclaimer
    This is a frontend-only demo project
    Authentication is simulated and not production-grade
    Intended for learning and demonstration purposes
📌 Future Enhancements
    Backend integration (Node.js / Express)
    Database upgrade (MongoDB / MySQL)
    JWT authentication
    Cloud image storage (Firebase / AWS)
    Deployment as full-stack application
📄 License
    This project is intended for educational use only.
