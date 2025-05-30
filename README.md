
````markdown
# 🔍 InsightSpy – Dark Pattern Detection Web Extension

**InsightSpy** is a browser extension that detects **dark patterns** on e-commerce websites and alerts users in real-time. Built using **vanilla JavaScript**, it aims to promote ethical design awareness and protect consumers from manipulative UI/UX practices.

---

## 🚀 Features

- 🧠 Detects common **dark patterns** like forced continuity, disguised ads, confirm shaming, and more.
- ⚡ Real-time **alerts and warnings** when a dark pattern is detected.
- 📸 Lightweight image-based indicators for detected patterns.
- 🖥️ Compatible with both **Chrome** and **Firefox** (separate configurations provided).
- 📊 Minimal, intuitive UI that integrates directly into the browsing experience.

---

## 📂 Project Structure

```bash
InsightSpy/
│
├── chrome/               # Chrome-specific build
│   ├── manifest.json
│   ├── popup.html
│   ├── popup.js
│   ├── icons/
│   └── content.js
│
├── firefox/              # Firefox-specific build
│   ├── manifest.json
│   ├── popup.html
│   ├── popup.js
│   ├── icons/
│   └── content.js
│
├── assets/               # Images and illustrations
│   └── dark-pattern-examples/
│
└── README.md             # This file
````

---

## 🧪 How It Works

1. **Content script** scans the webpage DOM for visual or structural dark patterns.
2. When patterns are found, **highlighted warnings** or overlay messages are shown.
3. Users can click the extension icon to view a breakdown of detected patterns.

---

## 🛠️ Technologies Used

* **JavaScript** (vanilla)
* **HTML/CSS**
* **Chrome & Firefox WebExtension APIs**

---

## 🧑‍💻 Installation (for Developers)

### Chrome

1. Go to `chrome://extensions`
2. Enable **Developer Mode**
3. Click **Load unpacked** and select the `/chrome` directory.

### Firefox

1. Go to `about:debugging#/runtime/this-firefox`
2. Click **Load Temporary Add-on**
3. Select the `manifest.json` inside the `/firefox` directory.

---

## 🎯 Use Cases

* Educating users and designers about unethical design.
* Enhancing transparency for e-commerce shoppers.
* Promoting responsible design practices in digital products.

---

## 🏆 Awards & Recognition

* 🥇 **1st Place – Envisage Project Expo 2024** (MJCET)
* 💡 Recognized for innovation in consumer protection and ethical tech.

---

## 📬 Contact

Created by **Yasir Hussain**
📧 [yasirhussain0027@gmail.com](mailto:yasirhussain0027@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/yasirhussain027)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

