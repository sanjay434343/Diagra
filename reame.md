# 🌱 Pollinations Random Content Generator

A simple web app that uses the [Pollinations API](https://text.pollinations.ai/) to load random AI-generated content, either in **text** or **image** form — great for creative ideas, symbol art, or surprise visuals.

---

## ✨ Features

- 🎲 Loads **random AI-generated content**
- 📜 Uses `https://text.pollinations.ai/hello/[prompt]` for creative text
- 🖼 Optionally uses `https://image.pollinations.ai/prompt/[prompt]` for visual output
- 🎨 Supports ASCII/symbol-style content and surreal image prompts
- ⚡ Instant in-browser generation (no login required)

---

## 🔧 Example Usage

**Text API:**

```js
fetch("https://text.pollinations.ai/hello/random prompt")
  .then(res => res.text())
  .then(data => console.log(data));
