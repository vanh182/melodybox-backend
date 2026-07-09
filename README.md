# 🎵 Melodybox Backend

> A RESTful backend service for the Melodybox music streaming application, built with Node.js, Express.js, and MongoDB.

![Node.js](https://img.shields.io/badge/Node.js-18+-green?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-REST_API-black?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb)
![Mongoose](https://img.shields.io/badge/Mongoose-ODM-red)

---

# 📖 Overview

Melodybox Backend is a RESTful API service that powers the Melodybox music streaming application.

The backend manages songs, playlists, and music categories while serving audio files and album artwork. Built with Express.js and MongoDB, the project follows a clean REST architecture that is easy to maintain and extend.

---

# ✨ Features

* 🎵 Song Management
* 📂 Music Category Management
* 🎼 Playlist Management
* 🖼 Album Artwork Hosting
* 🎧 Audio File Streaming
* 🌐 RESTful APIs
* ☁ MongoDB Data Storage

---

# 🛠 Tech Stack

| Category      | Technologies |
| ------------- | ------------ |
| Runtime       | Node.js      |
| Framework     | Express.js   |
| Database      | MongoDB      |
| ODM           | Mongoose     |
| Configuration | dotenv       |

---

# 🏗 Architecture

```text
Mobile Application
        │
        ▼
 REST API (Express.js)
        │
        ▼
 Business Logic
        │
        ▼
 MongoDB Database
```

---

# 📂 Project Structure

```text
MelodyboxBE
├── audios/
├── images/
├── models/
├── routes/
├── index.js
├── package.json
└── README.md
```

---

# 📸 Screenshots/API Modules

## API Modules

The backend exposes RESTful APIs for the following modules:

| Module     | Description                 |
| ---------- | --------------------------- |
| Songs      | Retrieve and manage songs   |
| Categories | Manage music categories     |
| Playlists  | Create and manage playlists |
| Audio      | Stream audio files          |

> Add screenshots from Postman, Swagger, or your mobile application if available.

---

# 🚀 How to Run

## Prerequisites

* Node.js 18+
* MongoDB

## Clone the repository

```bash
git clone https://github.com/vanh182/melodybox-backend.git
cd melodybox-backend
```

## Install dependencies

```bash
npm install
```

## Configure environment variables

Create a `.env` file:

```env
MUSIC_DB_URI=your_mongodb_connection_string
```

## Start the server

```bash
npm start
```

The application will run at:

```text
http://localhost:3000
```

---

# 🚀 Future Improvements

* JWT Authentication
* Favorite Songs
* Search and Filtering
* Pagination
* Music Recommendation
* Docker Deployment
* Swagger / OpenAPI Documentation

---

# 📄 License

This project is licensed under the MIT License.

Feel free to use, modify, and distribute this project for educational and personal purposes.
