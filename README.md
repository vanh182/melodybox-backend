# 🎵 Melodybox Backend

> A RESTful backend service for the Melodybox music streaming application, built with Node.js, Express.js, and MongoDB.

![Node.js](https://img.shields.io/badge/Node.js-18+-green?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-REST_API-black?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb)
![Mongoose](https://img.shields.io/badge/Mongoose-ODM-red)

---

# 📖 Overview

Melodybox Backend provides RESTful APIs for a music streaming application.

The backend manages songs, playlists, and music categories while serving audio files and album artwork to the mobile application.

The project follows a simple REST architecture using Express.js and MongoDB, making it easy to extend and maintain.

---

# ✨ Features

- 🎵 Song Management
- 📂 Music Category Management
- 🎼 Playlist Management
- 🖼 Album Artwork Hosting
- 🎧 Audio File Streaming
- 🌐 RESTful APIs
- ☁ MongoDB Data Storage

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Runtime | Node.js |
| Framework | Express.js |
| Database | MongoDB |
| ODM | Mongoose |
| Configuration | dotenv |

---

# 🏗 System Architecture

```text
Mobile Application
        │
        ▼
   REST API (Express)
        │
        ▼
Business Logic
        │
        ▼
 MongoDB Database
```

<p align="center">
<img src="./images/system_architecture.png" width="85%">
</p>

> Replace the image above with an architecture diagram if available.

---

# 📂 Project Structure

```text
MelodyboxBE
│
├── audios/
├── images/
├── models/
│     ├── songs.js
│     ├── playlist.js
│     └── categories.js
├── routes/
├── index.js
├── package.json
└── README.md
```

---

# 🎼 Core Modules

## 🎵 Songs

Manage song information including:

- Song title
- Artist
- Album artwork
- Audio file
- Category

---

## 📂 Categories

Group songs into different music genres or collections.

Examples:

- Vietnamese Music
- US-UK Music
- French Music

---

## 🎧 Playlists

Provide APIs for playlist creation and management.

Playlists allow users to organize songs into personalized collections.

---

# 🌐 REST APIs

Example API modules include:

| Module | Description |
|---------|-------------|
| Songs | Retrieve and manage songs |
| Categories | Manage music categories |
| Playlists | Create and manage playlists |
| Audio | Stream audio files |

> Actual API endpoints may vary depending on the project version.

---

# 🚀 Getting Started

## Clone the repository

```bash
git clone https://github.com/vanh182/melodybox-backend.git
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

The backend will run on:

```text
http://localhost:3000
```

---

# 📈 Highlights

- RESTful API design
- Express.js architecture
- MongoDB integration with Mongoose
- Static image hosting
- Static audio hosting
- Clean project organization

---

# 🚀 Future Improvements

- User authentication (JWT)
- Favorite songs
- Search and filtering
- Pagination
- Music recommendation
- Docker deployment
- API documentation with Swagger/OpenAPI

---
