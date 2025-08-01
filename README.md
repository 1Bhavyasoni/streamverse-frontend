Absolutely! Here’s the complete, clean, and ready-to-paste README.md for your Frontend Repository (streamverse-frontend) in a single Markdown code block:

# 🎬 Streamverse – Netflix 2.0 Clone (Frontend)

A full-featured Netflix clone built using **React**, **Redux**, **Tailwind CSS**, and **TMDB API**, with authentication, search, and streaming UI integrated.

---

## 🌐 Live Preview

🔗 [Visit Streamverse Frontend](https://streamverse-frontend.vercel.app)

📦 [Backend Repo](https://github.com/1Bhavyasoni/streamverse-backend)  
🟢 [Backend Live API](https://streamverse-backend-nw9k.onrender.com/api/v1/user)

---

## 📸 Screenshot

<img width="1468" height="874" alt="Image" src="https://github.com/user-attachments/assets/a90c7e82-b852-43cb-b6b9-a1af09ec215a" /> <!-- Replace with actual image path or uploaded GitHub image link -->

---

## 🚀 Features

- 🔐 User Authentication (Signup/Login)
- 🍿 Browse Trending, Popular, Upcoming, and Top-Rated Movies
- 🎥 Movie Trailers and Thumbnails from TMDB
- 🔍 Search movies
- 🎯 Responsive design
- 🧠 Global state with Redux Toolkit

---

## 🔧 Run Locally

```bash
git clone https://github.com/1Bhavyasoni/streamverse-frontend.git
cd streamverse-frontend
npm install
npm start
```

---

## ⚙️ Update Backend API Endpoint

**In `/src/utils/constant.js`**, update the API base URL:

```js
export const API_END_POINT = "https://streamverse-backend-nw9k.onrender.com/api/v1/user";
```

---

## 📦 Tech Stack

- **Frontend:** React.js, Redux, Tailwind CSS  
- **Backend:** Node.js, Express.js, MongoDB (via Render – see backend repo)

---

## 📁 Folder Structure

```
src/
│
├── components/
│   ├── Login.js
│   ├── Browse.js
│   ├── MovieList.js
│   └── ...
├── hooks/
│   └── useNowPlayingMovies.js
├── redux/
│   ├── store.js
│   └── userSlice.js
├── utils/
│   └── constant.js
├── index.js
└── App.js
```

---

## 🛠️ Environment Setup

No environment variable is required unless using private TMDB keys.

Optional:

```env
REACT_APP_TMDB_KEY=your_tmdb_key
```

---

## 👤 Developer

**Bhavya Soni**  
[🔗 LinkedIn](https://www.linkedin.com/in/bhavya-soni-9684b3229/)
