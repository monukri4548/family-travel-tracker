# 🗺️ Visited Countries Tracker App

This is a Node.js + Express web app that allows users to track countries they've visited. Each user can maintain their own travel log, which is stored in a PostgreSQL database. You can switch between users or add new ones dynamically.

---

## 🚀 Features

- 🌍 Add countries to a personal visited list
- 👤 Support for multiple users
- 🎨 Choose a color theme per user
- 💾 PostgreSQL-based data persistence
- 🧠 Smart country name search using partial matches
- 🖼️ Renders dynamic EJS templates with user-specific info

---

## 🧩 Tech Stack

- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **Templating**: EJS
- **Middleware**: body-parser, express-static

---

## 📁 Project Structure

/visited-countries-app
│
├── public/ # Static assets (e.g. CSS, JS)
├── views/ # EJS templates
│ ├── index.ejs
│ ├── new.ejs
│
├── app.js # Main server file
├── package.json
└── README.md


## ⚙️ PostgreSQL Setup

### Tables Required
Note: Prepopulate the countries table with ISO 3166-1 country codes and names.

📦 Installation
git clone https://github.com/your-username/visited-countries-app.git
cd visited-countries-app
npm install

🧪 Run the App
node app.js
Then open your browser and go to:
http://localhost:3000
