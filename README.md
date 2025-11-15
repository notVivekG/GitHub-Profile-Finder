# 🌐 GitHub Profile Finder

A simple and elegant web app that lets you **search for any GitHub user** and view their profile details instantly — including avatar, name, followers, and public repositories — using the **GitHub API**.

---

## 🖼️ Preview

![GitHub Profile Finder Screenshot](./screenshot.png)  

---

## 🚀 Features

- 🔍 Search any GitHub username instantly  
- 📸 Displays user avatar, name, username, followers, and public repos  
- 🌐 Direct link to the user’s GitHub profile  
- ⚡ Built with **Tailwind CSS** for modern styling  
- 💻 Uses **Fetch API** to retrieve live data  

---

## 🧰 Tech Stack

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structure and layout |
| **Tailwind CSS** | Styling and responsiveness |
| **DaisyUI** | Tailwind CSS plugin that provides pre-built UI components |
| **JavaScript (Fetch API)** | Fetching and displaying GitHub data |
| **GitHub API** | Data source |

---

## 📦 Getting Started

### 1️⃣ Clone this repository
```bash
git clone https://github.com/notVivekG/GitHub-Profile-Finder.git
cd GitHub-Profile-Finder
```

2️⃣ Install dependencies (if using Tailwind CLI)

If you used Tailwind via CDN, skip this step.
Otherwise, if you generated output.css using Tailwind CLI:
```bash
npm install
npx tailwindcss -i ./input.css -o ./output.css --watch
```

⚙️ How It Works

Enter a GitHub username in the input field.
Click Search.

The app fetches data from the GitHub API endpoint:
```bash
https://api.github.com/users/<username>
```
---

## 💡 Future Improvements

- Add dark/light theme toggle 🌗
- Display recent repositories 🧩
- Improve error handling for API rate limits 🚫
- Add loading animation ⏳

---


🌟 Show your support
If you like this project, star ⭐ the repository to support its development!

Made with ❤️ using HTML, Tailwind CSS, Daisy Ui (lib) and JavaScript
