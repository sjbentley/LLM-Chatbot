# AI Chatbot: Next-Gen Conversational AI Experience
---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture & Tech Stack](#architecture--tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Overview

Welcome to the future of interactive communication. **{BENTLEY}** is an advanced, innovative, and disruptive conversational AI application that delivers a next-generation chat experience through seamless integration of code intelligence, dynamic file uploads, and adaptive theming. Designed for developers and innovators, this project transforms ordinary chat interfaces into a powerful, multi-functional tool.

This application leverages cutting-edge generative language technology to provide:

- Instant responses with simulated typing effects.
- Automatic formatting of code blocks with syntax highlighting.
- Seamless file uploads and previews.
- An adaptive theme toggle for light and dark modes.

It’s built with pure HTML, CSS, and JavaScript—making it lightweight yet powerful—while employing advanced features that set a new standard for chat interfaces.

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
   git clone https://github.com/sjbentley/llm_chatbot.git

    Navigate to the Project Directory:

cd llm_chatbot

Place Your API Key:

The API key and URL are defined in script.js. You can update these values:

// In script.js
const API_KEY = "YOUR_API_KEY_HERE";
const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=${API_KEY}`;

Open the Application:

Simply open index.html in your web browser. Alternatively, you can serve the files using a simple HTTP server:

    npx http-server .

    Then navigate to http://localhost:8080 (or whichever port is shown).

## Usage

    Chat Interaction: Type your query into the prompt input and press Enter or click the send button. For example, try asking for a Python script to retrieve ticker prices.

    File Upload: Click the attach file button to upload a file. Uploaded files will be shown as a preview or as a file icon with the file name.

    Theme Toggle: Click the theme toggle button to switch between light and dark modes.

## Project Structure

/frontend
  ├── index.html         # Main HTML file
  ├── style.css          # Stylesheet for the application
  ├── script.js          # JavaScript code for the chatbot functionality
  ├── favicon/           # Folder containing favicon images
  └── img/               # Folder containing additional images (e.g., avatars, logos)

## Configuration

    API Integration: The application sends chat history and user input to a generative language API. Update the API URL and key in script.js to match your API provider.

    Theme and Preferences: User theme preferences are saved using local storage.

    Copy Code Functionality: The code block handling function uses Prism.js for syntax highlighting. Make sure the Prism.js library is loaded via the <head> of your HTML file.

## 🕸️ Snippets

Key snippets from the project will be added here.

## 🔗 Links

- [Project Demo](#) *(Coming Soon)*

## 🚀 More

For further questions or feature requests, open an issue in the repository. 🚀

## License

This project is licensed under the MIT License.
