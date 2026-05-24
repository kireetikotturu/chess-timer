# Elite Multi-Player Arena Clock ⏳

A highly responsive, modern, and distraction-free digital game timer built for chess, speed cubing, board games, and multi-player matches. Designed to scale seamlessly from tiny mobile screens up to tablets and laptops.

🔗 **Live Application:** [chess-timer1.netlify.app](https://chess-timer1.netlify.app/)

---

## 🚀 Key Features

* **Dynamic Multi-Player Grid:** Supports **2, 3, or 4 players** with custom automated UI structural layout scaling.
* **Smart Orientation Control:** Includes a **Face to Face** inversion mode (flips Player 1 by 180° for single-phone tabletop battles) and **Side by Side** mode (perfect for laptops/tablets).
* **Advanced Timing Options:** Supports **Sudden Death**, **Bronstein Delay**, and **Fischer Bonus** increments with exact down-to-the-second clean matching countdown structures.
* **100% Offline-Resilient:** Continuously backs up match states to the browser's local memory database. If you accidentally **refresh the page**, or **minimize the app**, your match times safely pause and stay locked.
* **Audio Notifications Engine:** Synthesizes low-latency audio warning alert frequencies at 30 seconds remaining, 10 seconds remaining, turn switches, and match ends.

---

## 🛠️ Tech Stack & Implementation Details

* **Language Structure:** Pure Single-File Static HTML5 & Semantic DOM Layout Frameworks.
* **Style Compositing:** Responsive CSS Grid Matrix & Flexbox layout models utilizing uniform system fluid type sizing scaling (`clamp`).
* **Logic Engine:** Vanilla JavaScript tracking state arrays with structural interval loop checks running at a high-performance 100ms cycle rate.
* **Sound Generation:** Powered by the native browser **Web Audio API** (synthesizes audio oscillator tracks on the fly without loading heavy MP3 asset tracking).

---

## 👨‍💻 How to Run This Locally

1. Clone this repository link to your machine workspace:
```bash
   git clone [https://github.com/kireetikotturu/chess-timer.git](https://github.com/kireetikotturu/chess-timer.git)
