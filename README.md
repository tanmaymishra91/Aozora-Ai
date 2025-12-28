# 🚀 AozoraAi Chatbot

A premium, single-file AI chatbot interface powered by the **Perplexity API** (Sonar model).  
Designed with a sleek **Cyberpunk/Neon aesthetic**, robust markdown support, and a responsive mobile-first UI.

![AozoraAi Preview](https://aozoradesu.com/Ai)

## ✨ Features

*   **⚡ Real-time Streaming**: Responses stream in character-by-character with a smooth typewriter effect.
*   **🧠 Intelligent Context**: Remembers conversation history (stored locally in browser).
*   **📝 Rich Markdown Support**: 
    *   Syntaxes highlighting for code blocks (Python, JS, HTML, etc.)
    *   **Bold**, *Italic*, Headers, Lists, and Blockquotes.
    *   Auto-linking of URLs.
*   **🖼️ Image Analysis**: Support for uploading and analyzing images (Vision capabilities).
*   **📱 Mobile Responsive**: Fully optimized for touch devices with adaptive layouts.
*   **🎨 Premium UI**:
    *   Glassmorphism design.
    *   Neon accents (`#00ff88`).
    *   Smooth animations (fade-ins, typing indicators).
*   **🛠️ Utilities**:
    *   **Copy Code**: One-click copy for code blocks.
    *   **Export Chat**: Download conversation history as `.txt`.
    *   **Clear Chat**: "Hard Reset" button to wipe memory and reload.

## 🚀 Getting Started

### Prerequisites

*   A modern web browser (Chrome, Edge, Firefox, Safari).
*   An active **Perplexity API Key**.

### Installation

1.  **Clone or Download** this repository.
2.  Open `chatbot.html` in your text editor.
3.  Locate the configuration section at the top of the script:
    ```javascript
    const PPLX_API_KEY = "YOUR_API_KEY_HERE";
    ```
4.  Replace the placeholder with your actual API key.
5.  **Run**: Simply double-click `chatbot.html` to open it in your browser!

## 🎮 Usage

*   **Chat**: Type your message and hit Enter or the Send button.
*   **Upload**: Click the `+` icon to upload an image for analysis.
*   **Stop**: Click the red Stop button to interrupt a generating response.
*   **Clear**: Click the specific "Clear" icon in the header to wipe history and start fresh.

## 🛠️ Technology Stack

*   **HTML5 & CSS3**: Custom responsive grid and layouts.
*   **JavaScript (ES6+)**: Vanilla JS for zero-dependency bloat.
*   **Prism.js**: For beautiful code syntax highlighting.
*   **Perplexity API**: `sonar` model for intelligence.

## 📝 License

This project is free to use and modify. Enjoy!
