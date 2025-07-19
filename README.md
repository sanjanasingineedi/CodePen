
# 💻 CodePen Clone – A Real-Time HTML/CSS/JS Code Editor

A lightweight, responsive, real-time web code editor built using **vanilla HTML, CSS, and JavaScript** with syntax-highlighted editing via **CodeMirror**. This project mimics the core functionality of [CodePen](https://codepen.io), allowing users to prototype and preview HTML, CSS, and JavaScript in a single interface.

---

## 📖 Overview

The CodePen Clone provides an in-browser environment for writing and previewing HTML, CSS, and JavaScript with real-time output. Designed using native web technologies, it features a minimalistic layout, **dark/light theme toggle**, **expandable output section**, and **live iframe rendering**. The goal is to help learners and developers quickly test code snippets in a clean, responsive, and interactive environment without using external frameworks.

---

## 🎯 Features

- ✍️ **Three-Slot Code Editor** – Separate editable areas for HTML, CSS, and JS using CodeMirror.
- 🔄 **Live Output Preview** – Re-renders automatically in an embedded iframe as the user types.
- 🌗 **Dark/Light Theme Toggle** – User-friendly interface with a single-click theme switcher.
- 📱 **Responsive Layout** – Uses flexbox to support desktop and mobile views.
- ⛶ **Output Expand/Shrink** – Toggle full-screen mode for the output section.
- ⚡ **Zero Frameworks** – Built without React, Vue, or Angular – 100% native JS.

---

## 🛠 Technologies Used

| Tech         | Purpose                                      |
|--------------|----------------------------------------------|
| **HTML**     | Structuring the user interface               |
| **CSS**      | Styling and layout, including dark mode      |
| **JavaScript** | Real-time code injection and user interaction |
| **CodeMirror** | Rich code editor experience with syntax highlighting |
| **iframe**   | Safe and isolated real-time output rendering |

---

## 🧪 How It Works

1. **Code Input:**
   - HTML, CSS, and JavaScript editors powered by CodeMirror
   - Syntax highlighting and line numbering included

2. **Real-Time Output:**
   - Combines input into a single HTML string
   - Injects it into an iframe using `.write()` for immediate rendering

3. **Dark Mode Toggle:**
   - Button toggles a `dark` class on the `<body>`
   - CSS updates the appearance accordingly

4. **Output Fullscreen Toggle:**
   - Expand button enlarges output to full screen
   - Shrink button returns to normal view

---

## 📦 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/codepen-clone.git
cd codepen-clone
```

### 2. Open in Browser

Just open `index.html` in any modern browser – no server needed!

---

## ⚠️ Challenges Faced

- Dynamic iframe rendering without causing script injection issues
- Smooth CodeMirror integration with separate modes
- Responsive layout with flexbox for all devices
- Maintaining real-time sync while minimizing lag
- Toggle between dark and light themes without visual glitches

---

## 💡 How It’s Unique

- ⚙️ **No External Frameworks:** Pure HTML/CSS/JS
- 🧪 **Educational Tool:** Ideal for beginners learning how the web works
- 🌓 **Customizable Themes:** User-controlled dark/light mode
- 🎯 **Performance Focused:** Lightweight and fast

---

## 🔍 What's Next

- 💾 Add local storage support to save code across sessions
- ⬆️ Enable export/download of code snippets

---

## 👤 Author

**Sanjana Singineedi**  
[GitHub](https://github.com/sanjanasingineedi)  
📧 sanjanasingineedi0508@gmail.com

---

## 🏁 Conclusion

This CodePen clone project highlights the power of combining **CodeMirror, iframe rendering, and native JS** to build a complete, responsive, and user-friendly in-browser code editor. Its simplicity and flexibility make it a useful learning tool and a great demonstration of frontend development fundamentals.

---
