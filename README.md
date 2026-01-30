# Open Source Mentor

Open Source Mentor is a beginner-friendly web app that helps new developers discover their first open-source issues using the GitHub REST API.

It analyzes a user’s GitHub activity to determine their most-used programming language and then recommends open, beginner-friendly issues (`good first issue`, `beginner`) in that language.

---

## 🚀 Features

- Analyze GitHub repositories to detect the most-used language
- Fetch beginner-friendly open issues across GitHub
- Supports optional GitHub token to avoid API rate limits
- Simple, lightweight, and beginner-friendly UI

---

## 🛠️ Tech Stack

- HTML
- Tailwind CSS
- JavaScript
- GitHub REST API

---

## 📸 Screenshot

_Add a screenshot of the app here_

---

## 🌐 Live Demo

_Add your deployed link here (GitHub Pages / Netlify / Vercel)_

---

## 🔧 How It Works

1. (Optional) The user provides a GitHub Personal Access Token.
2. The app fetches the user’s repositories using the GitHub API.
3. It calculates the most frequently used programming language.
4. It searches GitHub for open issues labeled as beginner-friendly in that language.
5. The issues are displayed with direct links to GitHub.

---

## ▶️ Run Locally

No build tools are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/open-source-mentor.git
