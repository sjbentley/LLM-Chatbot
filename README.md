# AI Chatbot: Next-Gen Conversational AI Experience
---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture & Tech Stack](#architecture--tech-stack)
- [Installation](#installation)
- [License](#license)

## Overview

Welcome to the future of interactive communication. **{BENTLEY}** is an advanced, innovative, and disruptive conversational AI application that delivers a next-generation chat experience through seamless integration of code intelligence, dynamic file uploads, and adaptive theming. Designed for developers and innovators, this project transforms ordinary chat interfaces into a powerful, multi-functional tool.

This application leverages cutting-edge generative language technology to provide:

- Instant responses with simulated typing effects.
- Automatic formatting of code blocks with syntax highlighting.
- Seamless file uploads and previews.
- An adaptive theme toggle for light and dark modes.

It’s built with pure HTML, CSS, and JavaScript—making it lightweight yet powerful—while employing advanced features for chat interfaces.

---

## Features

- **Real-Time Conversational AI:** Engage with a state-of-the-art generative language model in real time.
- **Intelligent Code Block Handling:** 
  - Automatically detects Markdown-style code blocks.
  - Formats code using `<pre><code>` tags with [Prism.js](https://prismjs.com/) for syntax highlighting.
  - Provides an intuitive “Copy” button for easy code extraction.
- **File Upload & Preview:** Attach images and documents on the fly with built-in preview functionality.
- **Theme Toggle:** Switch seamlessly between dark and light modes to match your environment.
- **Responsive & Adaptive UI:** Designed to work flawlessly on desktop and mobile, delivering a clean, modern experience.

---

## Architecture & Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Syntax Highlighting:** [Prism.js](https://prismjs.com/)
- **File Handling:** HTML5 FileReader API
- **Generative Language API:** Gemini 1.5 Flash via Google’s Generative Language API
- **State Management:** In-browser state and DOM manipulation
- **Responsive Design:** Leveraging CSS Flexbox and Media Queries

---

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/sjbentley/LLM-Chatbot.git

    Navigate to the Project Directory:

   cd LLM-Chatbot

Place Your API Key:

The API key and URL are defined in script.js. You can update these values:

```bash
// In script.js
const API_KEY = "YOUR_API_KEY_HERE";
const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=${API_KEY}`;
```
Open the Application:

Simply open index.html in your web browser. Alternatively, you can serve the files using a simple HTTP server:

    npx http-server .

    Then navigate to http://localhost:8080 (or whichever port is shown).


## Project Structure
```bash
/frontend
  ├── index.html         # Main HTML file
  ├── style.css          # Stylesheet for the application
  ├── script.js          # JavaScript code for the chatbot functionality
  ├── favicon/           # Folder containing favicon images
  └── img/               # Folder containing additional images (e.g., avatars, logos)
```

## 🕸️ Snippets

Key snippets from the project will be added here.

## 🔗 Links

- [Project Demo](#) *(Coming Soon)*

## 🚀 More

For further questions or feature requests, open an issue in the repository. 🚀

## License

This project is licensed under the MIT License.
