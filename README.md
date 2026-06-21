# Prompt Optimizer

A simple, single-page web tool that helps you build well-structured AI image-generation prompts. Pick a subject, an art style, and a lighting mood, and it assembles a clean, ready-to-use prompt string — built by **Digital Solution**.

🔗 **Live demo:** _add your GitHub Pages link here after deploying_

## ✨ Features

- Free-text subject/character input
- Dropdown presets for art style (Cinematic Portrait, Editorial, Minimalist Studio)
- Dropdown presets for lighting & tone (Dramatic, Soft Studio, Neon Cyberpunk)
- Editable quality/resolution string
- One-click "Generate Prompt" + "Copy to Clipboard"
- Dark, distraction-free UI built with Tailwind CSS (via CDN)

## 🚀 Getting Started

This is a static, single-file app — no build step, no dependencies to install.

### Run locally

```bash
git clone https://github.com/<your-username>/prompt-optimizer.git
cd prompt-optimizer
```

Then just open `index.html` in your browser, or serve it locally:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

### Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your site will be live at `https://<your-username>.github.io/prompt-optimizer/` within a minute or two.

## 🛠️ Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (CDN build)
- Vanilla JavaScript

## 📂 Project Structure

```
prompt-optimizer/
├── index.html      # entire app (markup, styles, logic)
├── README.md
└── LICENSE
```

## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
