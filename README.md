# PAMANA - Web Edition 🎮🇵🇭

**PAMANA** is an educational 2D adventure RPG highlighting Philippine cultural heritage, historical artifacts, museum exploration, and trivia quiz battles.

Built with **Unity (WebGL / Universal Render Pipeline 2D)**.

---

## 🌐 Play in Browser (GitHub Pages)

You can play PAMANA directly in your web browser!

### How to Enable GitHub Pages for this Repository:
1. Navigate to your repository settings: [Repository Settings > Pages](https://github.com/nouzen214/capstone-pamana-game/settings/pages).
2. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/(root)`
3. Click **Save**.
4. Once GitHub Pages finishes deploying, your game will be playable at:
   👉 **`https://nouzen214.github.io/capstone-pamana-game/`**

---

## ⌨️ Controls & Gameplay

- **Movement:** `W`, `A`, `S`, `D` or Arrow Keys
- **Interact / Inspect Artifacts / Talk:** `E`
- **Bag / Inventory:** `B`
- **Pause / In-Game Menu:** `Esc`
- **Quiz Battles:** Mouse click on answer buttons (or use keyboard selection)
- **Fullscreen:** Click the fullscreen button in the bottom-right corner of the player

---

## 💻 Running Locally

If you clone this repository and want to run it locally on your computer:

### Option 1: Python HTTP Server (Windows Batch File)
Double click `run_webgl.bat` or execute in PowerShell:
```bash
python serve_webgl.py
```
Then open [http://localhost:8000](http://localhost:8000) in your browser.

### Option 2: Node.js (npx serve / http-server)
```bash
npx serve .
```

---

*Developed by UPHSL CCS - PAMANA Team.*
