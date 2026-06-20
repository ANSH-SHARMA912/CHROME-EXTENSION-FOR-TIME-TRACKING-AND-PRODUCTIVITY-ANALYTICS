# ⏱️ TimeTrack Pro - Chrome Extension for Time Tracking & Productivity Analytics

*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: ANSH SHARMA
*INTERN ID*:CTIS6655
*DOMAIN*: FULL STACK WEB DEVELOPMENT
*DURATION*: 16 WEEKS
*MENTOR*: NEELA SANTOSH

*OUTPUT*:

![image align]()

> A Chrome Extension that automatically tracks the time spent on different websites, classifies browsing activity, and provides insightful productivity analytics through a web dashboard.

---

## 📣 About

TimeTrack Pro is a browser extension built to help users understand how they spend their time online.

The extension automatically tracks browsing sessions, categorizes websites as **Productive**, **Neutral**, or **Unproductive**, securely stores user activity in a backend database, and visualizes productivity insights through an interactive dashboard.

Designed using **Chrome Extension APIs**, **Node.js**, **Express.js**, **MongoDB**, and **React.js**, the project demonstrates real-world browser extension development with backend integration and analytics.

---

# Table of Contents

* [Features](#features)
* [Technology Stack](#technology-stack)
* [Installation](#installation)
* [Using the Extension](#using-the-extension)
* [Dashboard Analytics](#dashboard-analytics)
* [Website Classification](#website-classification)
* [Project Structure](#project-structure)
* [Workflow](#workflow)
* [Future Enhancements](#future-enhancements)
* [Contributing](#contributing)
* [License](#license)

---

# Features

### Chrome Extension

* ⏱ Automatic website time tracking
* 🌐 Detects active browser tabs
* 📊 Tracks browsing duration in real-time
* 🔄 Background monitoring
* 💾 Stores browsing history securely
* 🔐 User authentication support

### Productivity Analytics

* Daily productivity summary
* Weekly productivity reports
* Total browsing time
* Productive vs Unproductive comparison
* Top visited websites
* Category-wise analytics
* Interactive charts and graphs

### Website Classification

The extension automatically categorizes websites.

### ✅ Productive

* GitHub
* LeetCode
* HackerRank
* GeeksforGeeks
* Stack Overflow
* Coursera
* Udemy

### ⚪ Neutral

* Gmail
* Google Docs
* Google Drive
* LinkedIn

### ❌ Unproductive

* Instagram
* Facebook
* X (Twitter)
* Netflix
* Reddit
* Snapchat

Users can customize these categories according to their preferences.

---

# Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript (ES6)

### Chrome Extension

* Manifest V3
* Chrome Tabs API
* Chrome Storage API
* Chrome Runtime API

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Dashboard

* React.js
* Chart.js

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/your-username/timetrack-pro.git
```

## Install Backend

```bash
cd backend
npm install
```

## Start Backend Server

```bash
npm start
```

## Run Dashboard

```bash
cd dashboard
npm install
npm start
```

## Load Chrome Extension

1. Open **Google Chrome**
2. Navigate to:

```
chrome://extensions
```

3. Enable **Developer Mode**
4. Click **Load Unpacked**
5. Select the **extension** folder

The extension is now ready to use.

---

# Using the Extension

1. Install the Chrome Extension.
2. Create or log in to your account.
3. Browse websites normally.
4. The extension automatically tracks the active tab.
5. Website activity is securely stored in the backend database.
6. Open the analytics dashboard to view productivity insights.
7. Check the weekly productivity report to monitor browsing habits.

---

# Dashboard Analytics

The dashboard provides:

* Total screen time
* Productive browsing time
* Unproductive browsing time
* Daily activity summary
* Weekly productivity report
* Top visited websites
* Website category distribution
* Productivity score
* Interactive charts

---

# Website Classification

Every visited website is classified based on predefined categories.

| Category     | Examples                    |
| ------------ | --------------------------- |
| Productive   | GitHub, LeetCode, Coursera  |
| Neutral      | Gmail, Google Docs          |
| Unproductive | Instagram, Facebook, Reddit |

Users can update categories from the dashboard.

---

# Project Structure

```text
TimeTrack-Pro/

├── extension/
│   ├── manifest.json
│   ├── background.js
│   ├── popup.html
│   ├── popup.js
│   ├── popup.css
│   └── icons/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── config/
│
├── dashboard/
│   ├── public/
│   └── src/
│
└── README.md
```

---

# Workflow

```
User Opens Browser
        │
        ▼
Extension Detects Active Tab
        │
        ▼
Track Website Usage
        │
        ▼
Categorize Website
        │
        ▼
Store Data in MongoDB
        │
        ▼
Generate Productivity Analytics
        │
        ▼
Display Dashboard Reports
```

---

# Weekly Productivity Report

The application automatically generates a weekly report containing:

* Total browsing time
* Productive hours
* Unproductive hours
* Productivity percentage
* Most visited websites
* Daily activity breakdown
* Website category distribution
* Weekly productivity trend

---

# Future Enhancements

* AI-powered productivity recommendations
* Focus mode
* Pomodoro timer integration
* Website blocking
* Goal tracking
* Email productivity reports
* Browser synchronization
* Dark mode
* Export analytics to PDF or CSV
* Mobile companion application

---

# Contributing

Contributions are welcome!

If you'd like to improve the extension, fix bugs, or add new features:

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# License

This project is developed for educational purposes as part of the **Chrome Extension for Time Tracking and Productivity Analytics** assignment.
