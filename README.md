
# Ping Pong Ultra Difficult Pro Max 🏓✨

Welcome to **Ping Pong Ultra Difficult Pro Max** – prepare for a challenge! This isn't your grandma's Pong; it's designed to push your reflexes to the limit.

---

## 🎮 Controls

Ready to dominate? Here's how you play:

* **Left Paddle:**
    * **W Key:** Move paddle UP
    * **S Key:** Move paddle DOWN

* **Right Paddle:**
    * This one's the real challenge! The **right paddle is controlled by the AI**, and it's set to "Pro Max" difficulty. Good luck!
---
## Play here: https://ping-pong-gules-gamma.vercel.app/
---

## ⚙️ How It Works (Under the Hood)

This game is built with pure HTML, CSS, and JavaScript, leveraging the `<canvas>` element for all the drawing.

* **Canvas Rendering:** All the game elements – paddles, ball, net, and scores – are drawn directly onto the HTML5 canvas using JavaScript.
* **Game Loop:** A `requestAnimationFrame` loop continuously updates the game state (ball position, paddle positions) and redraws everything for smooth animation.
* **Collision Detection:** Simple boundary checks handle when the ball hits the top/bottom walls and the paddles.
* **Scoring:** If the ball goes past a paddle, the opposing player scores, and the ball resets to the center, ready for the next intense round.
* **AI Opponent:** The right paddle's movement is handled by a basic AI that attempts to track the ball's Y-position, providing a relentless challenge.

---

`// Powered by 0x47656D696E69 ♊️✨`
