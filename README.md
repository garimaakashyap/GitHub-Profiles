<h1 align="center">👤 GitHub Profile Finder</h1>

<p align="center">
  <img src="screenshot.png" alt="GitHub Profile Finder Screenshot" width="600">
</p>

<p align="center">
  A sleek, responsive web app that fetches and displays any GitHub user’s profile and repositories using the GitHub API.
</p>

<p align="center">
  <a href="https://garimaakashyap.github.io/GitHub-Profiles/">🌐 Live Demo</a> |
  <a href="#features">✨ Features</a> |
  <a href="#tech-stack">🛠️ Tech Stack</a> |
  <a href="#getting-started">🚀 Getting Started</a> |
  <a href="#screenshots">📸 Screenshots</a> |
  <a href="#license">📄 License</a>
</p>

---

## 📌 About the Project

The **GitHub Profile Finder** is a modern and minimal web app that allows users to search for any GitHub profile and get real-time data like avatar, bio, number of followers, public repositories, and the most recently created repos.

This project is ideal for learning how to work with APIs, manage asynchronous requests, and build responsive UI layouts using only HTML, CSS, and JavaScript (no frameworks).

---

## ✨ Features

✔️ Search any GitHub user by username  
✔️ View profile avatar, name, bio, and stats  
✔️ Displays followers, following, and repo count  
✔️ Shows 5 most recently created repositories  
✔️ Error handling for invalid usernames  
✔️ Fully responsive layout for desktop and mobile  
✔️ Built with no external UI libraries or frameworks  

---

## 🖼️ Demo Preview

🔗 **Live Demo**: [Click here to try the app now!](https://garimaakashyap.github.io/GitHub-Profiles/)

<p align="center">
  <img src="app.png" alt="GitHub Profiles in Action" width="600">
</p>

---

## 🛠️ Tech Stack

| Technology     | Description                              |
|----------------|------------------------------------------|
| HTML5          | Markup for the structure                 |
| CSS3           | Styling and responsive design            |
| JavaScript (ES6) | App logic, API calls, and DOM updates |
| Axios          | For making HTTP requests to GitHub API   |
| GitHub API     | Source for profile and repo data         |

---

## 🧪 How to Use
1. **Open the app in your browser:**
🔗 https://garimaakashyap.github.io/GitHub-Profiles/

2. **Enter any GitHub username** in the search field (e.g., torvalds, gaearon, or your own username).

3. **Hit Enter** or submit the form.

4. The app will:

✔️ Fetch the user's public data from GitHub

✔️ Display their avatar, bio, and key statistics

✔️ List the 5 most recently created public repositories

5.  If the user does not exist, an elegant error card will be shown.

---

## 🧠 Behind the Scenes (Technical Details)
🔗 **API Integration**
The app uses the GitHub REST API to fetch user data:

GET https://api.github.com/users/{garimaakashyap}

GET https://api.github.com/users/{garimaakashyap}/repos?sort=created

📦 **Axios for Requests **

Instead of fetch(), this project uses Axios for:

Simpler syntax

Better error handling

Cleaner async/await patterns

🧩 **Dynamic HTML Generation**
DOM elements like the user card and repository links are dynamically created using template literals and JavaScript DOM methods.

📵 **Error Handling**
If the user is not found (404), an error card is displayed.

If repository fetching fails, an error message is shown.

---

## 📱 Responsive Design
Uses media queries for devices below 500px

Input and card components adapt for smaller screen sizes

Layout becomes vertical for better mobile readability

---

## ✨ Visual Aesthetics

Modern pink color palette (#f7bdd0, #ee9bb7)

Soothing shadows and rounded cards

Custom GitHub-inspired card layout

Use of Poppins font for a clean look



---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 📁 Clone the Repository
```bash
git clone https://github.com/garimaakashyap/GitHub-Profiles.git
cd github-profile-finder
```
---
## Contact

- **GeeksforGeeks Profile**: [Your gfg](https://www.geeksforgeeks.org/user/garimamillicent/)
- **LinkedIn**: [Your LinkedIn](https://www.linkedin.com/in/garima-kashyap-75b1202b8/)
- **GitHub**: [Your GitHub](https://github.com/garimaakashyap)
