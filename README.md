# 🔐 SanuVault

**SanuVault** is a lightweight, secure, and elegant file vault built with HTML, Tailwind CSS, and JavaScript. It allows you to upload, store (locally), and download personal files through a beautifully designed UI — with password protection.

Hosted directly on GitHub Pages.

---

## 🚀 Live Demo
🔗 [https://Sanu0910.github.io/sanuvault](https://Sanu0910.github.io/sanuvault)

---

## ✨ Features

- 🔐 Password-protected access (client-side only)
- 🧼 Clean and modern Tailwind CSS UI
- 📁 File upload and download (stored in browser's localStorage)
- 📱 Mobile responsive
- 💬 Password hint included
- ⚡ Fully static — perfect for GitHub Pages

---

## 📦 Usage

1. Clone or download this repo.
2. Open `index.html` to run locally or host on GitHub Pages.
3. Upload your personal files (stored locally in browser).
4. Click "Download" to access them later.

> ⚠️ Note: This is a front-end only project. File storage is handled via `localStorage` and not secure for sensitive data. For real security, use Firebase or server-side logic.

---

## 🔧 Customize

- Change password in `index.html`:
  ```js
  const PASSWORD = 'yourpassword';
