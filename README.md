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

* ### v0.6 - The "State Machine" Update
* **Mode Selection:** Added a pre-game menu to choose between 'Cozy' (Normal) and 'Rush Hour' (Hard).
* **Smart Loading:** Refactored the loading screen to use `sessionStorage`, so it only plays once per visit.
* **Vector Background:** Implemented a lightweight CSS-pattern background (45-degree stripes) with infinite rightward scrolling.
* **Chocolate Progression:** Added a "Chocolate Bar" at the bottom that fills up as you type, representing your progress toward completing the order.
* **Social Integration:** Restored the Local Leaderboard and Ghost Challenge systems.

* ### v0.6.5 - The "State & Palette" Update
* **UI State Machine:** Implemented a central "Start Screen" with navigation to Game, Difficulty, and Customization.
* **Palette System:** Added a customization engine allowing players to swap between 'Classic Espresso', 'Midnight Brew', and 'Forest Matcha' themes.
* **Mode Specialization:**
    * **Cozy Mode:** Focuses on the "Chocolate Progression" bar with a "Return to Menu" safety button.
    * **Rush Hour:** Re-implemented the "Heat Meter" (Customer Waiting Time) and added a looping order logic for endless play.
* **Bug Fix:** Refined the "Hard Mode" typo detection logic to prevent false "Game Over" triggers.
* **Transition System:** Re-purposed the loading screen as a "Travel transition" that plays whenever switching between the Menu and the Game.
  
### v0.6.7 - The "Grand Architecture" Update
* **State Machine:** Full menu navigation (Start -> Difficulty/Customize -> Game).
* **Version Engine:** Integrated a dropdown that toggles game features from v0.1 up to v0.6.7.
* **Rush Hour Refined:** * Fixed typo detection logic (no more false "Game Over").
    * Restored the Heat Meter (Time Limit) specifically for this mode.
* **Cozy Mode:** Focuses on the "Chocolate Progression" bar with a Menu return button.
* **Palette Engine:** Supports Classic, Midnight, and Matcha themes across all screens.
* **Transition Logic:** The loading screen now acts as a bridge between all menu states.
  
### v0.7 - The "Definitive Brew" Update
* **Unified State Machine:** Full menu navigation (Start -> Difficulty/Customize -> Game).
* **Sensory & Audio Engine:** * Integrated real-time BGM and SFX (Click, Ding, Error).
    * BGM triggers on first interaction for a seamless shift start.
* **Physics-Based UI:** Implemented "Bouncy Buttons" using `cubic-bezier` scaling.
    * Buttons size up on hover and compress on click.
* **Version Engine:** Integrated a dropdown that toggles game features from v0.1 up to v0.7.
* **Rush Hour Refined:** * Fixed typo detection logic (no more false "Game Over").
    * Restored the Heat Meter (Time Limit) specifically for this mode.
* **Cozy Mode:** Focuses on the "Chocolate Progression" bar with a Menu return button.
* **Palette Engine:** Supports Classic, Midnight, and Matcha themes across all screens.
* **Transition Logic:** The loading screen now acts as a bridge between all menu states.

---
*Created by KnightGG.*
