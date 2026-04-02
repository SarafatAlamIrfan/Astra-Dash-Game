# 🚀 Astro Dash (NRF26 Arcade)

A retro-styled, web-based arcade shoot-'em-up built with HTML5 Canvas and vanilla JavaScript. Defend against waves of enemies, compete for the high score, and secure your place on the global live leaderboard.

[![Play Astro Dash](https://img.shields.io/badge/Play_Now-Live_Demo-success?style=for-the-badge)](https://SarafatAlamIrfan.github.io/Astra-Dash-Game/)

## ✨ Features
* **Classic Arcade Gameplay:** Progressively difficult waves of enemies and increasing enemy speeds.
* **Global Leaderboard:** Real-time "Top 5 Agents" high scores powered by Firebase.
* **Cross-Platform Controls:** Full support for desktop keyboard controls and mobile touch-screen overlays with anti-zoom protections.
* **Retro Aesthetics:** Custom CRT scanline CSS overlay, neon glowing particle explosions, and custom arcade typography.
* **Anti-Cheat Mechanics:** Includes baseline score-to-time validation to deter basic browser console manipulation.

## 🛠️ Tech Stack
* **Frontend:** HTML5 `<canvas>`, Vanilla JavaScript (ES6+), Tailwind CSS (for UI overlay and responsive layout).
* **Backend/Database:** Firebase Realtime Database.
* **Typography:** Google Fonts (Orbitron, Rajdhani).

## 🎮 How to Play
* **Desktop:** Use the `Left` and `Right` arrow keys to move your ship. Press or hold `Spacebar` to fire.
* **Mobile:** Use the on-screen arcade buttons to navigate and shoot. 

## 🚀 Running Locally
This is a lightweight, single-file application. No complex build steps or local servers are required to run the game locally!

1. Clone the repository:
git clone [https://github.com/SarafatAlamIrfan/astro-dash.git](https://github.com/SarafatAlamIrfan/astro-dash.git)

2. Navigate to the project folder:

cd astro-dash

3. Open index.html directly in your favorite web browser.


## 🛡️ Database Configuration Note

This game utilizes Firebase for the global leaderboard. The client-side configuration keys are included in the source code, which is standard for Firebase web apps. Security is handled via Firebase Realtime Database Rules. If you are forking this project, ensure your Firebase rules validate incoming scores and prevent unauthorized global writes/deletes.
