# ☕ LatteTyper: The Barista Sprint

**LatteTyper** is a high-speed typing game where your keyboard is the espresso machine. Can you keep the coffee hot while customers bark complex orders at you?



## 🎮 How to Play

1.  **Start the Shift:** Click the "Start Machine" button to begin.
2.  **Type the Order:** A customer order will appear. You must type it **exactly** as shown (including punctuation and symbols).
3.  **Watch the Heat:** Every second that passes, your coffee loses temperature. Finish the order to "steam" the milk and reset the heat.
4.  **Accuracy Matters:** If your accuracy drops too low, you'll be fired on the spot!

## ✨ Features

* **Real-time WPM Tracking:** Monitor your typing speed as you play.
* **Motion Blur Effects:** Smooth CSS transitions that simulate the rush of a busy morning shift.
* **Adaptive Audio:** Dynamic sound synthesis that reacts to every keystroke (no external audio files needed!).
* **Challenge Mode:** Generate a "Ghost Link" to challenge your friends to beat your specific high score.
* **Local Leaderboard:** Saves your top 5 fastest shifts in your browser.

## 🛠️ Technical Stack

* **HTML5/CSS3:** Glassmorphism UI and motion blur animations.
* **JavaScript (Vanilla):** Game logic, WPM calculations, and `localStorage` integration.
* **Web Audio API:** Real-time sound synthesis for typing and feedback sounds.
* **GitHub Actions:** Automated deployment pipeline to GitHub Pages.

## 🚀 Deployment

This project is automatically deployed using GitHub Actions. To host your own:

1. Fork this repository.
2. Enable **GitHub Pages** in your repository settings.
3. Your game will be live at `https://your-username.github.io/your-repo-name/`.

## 📝 Development Log (Devlog)

### v0.1 - The "Cozy" Foundation
* Initial concept: Barista-themed typing trainer with basic input matching.

### v0.2 - The "Rush Hour" Update
* Implemented **Motion Blur** transitions and the **Heat Meter** survival mechanic.

### v0.3 - The "Sensory" Update
* Integrated **Web Audio API** for real-time sound synthesis (clicks and dings).
* Glassmorphism UI skin applied.

### v0.4 - The "Competitive" Update
* Added **Local Leaderboards** and **Ghost Challenge** system via URL parameters.

### v0.4.1 - The "Stability" Patch (Current)
* **Bug Fix:** Resolved the "Infinity WPM" exploit where typing instantly caused massive speed scores.
* **Logic Update:** WPM calculation now waits for a 2-second "warm-up" to ensure mathematical stability.
* **UI Update:** Added version branding directly to the game screen.

### v0.5 - The "Engine" Update (Current)
* **Dynamic Environment:** Implemented an infinite scrolling background using CSS transforms.
* **Speed Sync:** Connected the background animation speed to the WPM counter. As your typing intensity increases, the "city rush" speeds up.
* **Boot Sequence:** Added a 5-second simulated loading screen with a "Pre-heating" progress bar to enhance the "game-y" atmosphere.
* **UX Refinement:** Hidden the UI until the loading sequence is complete to ensure a smooth transition into gameplay.

---
*Created by KnightGG.*
