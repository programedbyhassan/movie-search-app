# 🎬 CineSearch — Movie Finder App

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TMDB](https://img.shields.io/badge/TMDB_API-01B4E4?style=for-the-badge&logo=themoviedatabase&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=for-the-badge&logo=github&logoColor=white)

A clean, responsive movie search app built with vanilla HTML, CSS, and JavaScript. Search millions of movies, explore by genre, view detailed info, and save your favorites — all in a single file with no frameworks or build tools.

**🔗 Live Demo:** [yourusername.github.io/movie-search-app](https://yourusername.github.io/movie-search-app)

---

## ✨ Features

- 🔍 **Movie Search** — Search by title using the TMDB API with real posters and ratings
- 🎭 **Genre Filters** — Browse by Action, Comedy, Horror, Sci-Fi, Romance, and more
- 📋 **Movie Details Modal** — View runtime, genres, tagline, rating, and overview
- ❤️ **Favorites System** — Save movies locally using `localStorage`, persists between sessions
- 🌙 **Dark / Light Mode** — Toggle between themes with smooth transitions
- 📈 **Trending on Load** — Displays this week's trending movies by default
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop

---

## 🖼️ Screenshots

> _Add screenshots here after deploying. You can use [screenshotone.com](https://screenshotone.com) or take them manually._

| Home (Dark Mode) | Search Results | Movie Detail |
|---|---|---|
| ![Home](screenshots/home.png) | ![Search](screenshots/search.png) | ![Modal](screenshots/modal.png) |

---

## 🚀 Getting Started

No installation or build step required.

### Option 1 — Open directly

```bash
# Clone the repo
git clone https://github.com/yourusername/movie-search-app.git

# Open in browser
open index.html
```

### Option 2 — Deploy to GitHub Pages

1. Fork or upload this repo to your GitHub account
2. Go to **Settings → Pages**
3. Set source to **main branch / root**
4. Your app is live at `https://yourusername.github.io/movie-search-app`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Structure and semantic markup |
| CSS3 | Styling, dark mode, responsive layout, animations |
| Vanilla JavaScript | DOM manipulation, API calls, localStorage |
| [TMDB API](https://www.themoviedb.org/documentation/api) | Movie data, posters, genres, ratings |

---

## 📁 Project Structure

```
movie-search-app/
│
├── index.html       # Entire app — HTML, CSS, and JS in one file
└── README.md        # You are here
```

---

## 🔑 API Reference

This project uses the free [TMDB API](https://www.themoviedb.org/documentation/api).

The API key included is a public demo key. To use your own:

1. Create a free account at [themoviedb.org](https://www.themoviedb.org)
2. Go to **Settings → API → Create**
3. Replace the `API_KEY` value in `index.html`:

```js
const API_KEY = 'your_api_key_here';
```

---

## 💡 What I Learned

- Fetching and handling data from a real REST API
- Building a responsive UI without any CSS framework
- Managing application state in vanilla JavaScript
- Persisting user data with `localStorage`
- Implementing dark/light mode with CSS custom properties
- Deploying a static site with GitHub Pages

---

## 🔮 Future Improvements

- [ ] Add pagination for search results
- [ ] Include TV show search alongside movies
- [ ] Add a "Watch Trailer" button via YouTube embed
- [ ] Sort favorites by rating or date added
- [ ] Add a loading skeleton instead of a spinner

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> Built with ❤️ as part of my web development portfolio.
> Data provided by [The Movie Database (TMDB)](https://www.themoviedb.org).
