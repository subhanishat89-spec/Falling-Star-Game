# Falling-Star-Game
An interactive browser game built with HTML5, CSS3, and JavaScript where players catch falling stars to build their score.
# Catch the Falling Stars ⭐

An interactive 2D browser mini-game developed as part of the **CSE 479: Web Programming** course at **East West University**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Live Demo
Play the game live directly in your browser:
**[https://subhanishat89-spec.github.io/Falling-Star-Game/](https://subhanishat89-spec.github.io/Falling-Star-Game/)**

---

## 🎮 How to Play

1. Click the **Start Game** button to begin.
2. Use the **Left Arrow (`←`)** and **Right Arrow (`→`)** keys on your keyboard to control the orange basket.
3. Catch the falling stars before they hit the ground.

### 🎯 Scoring & Mechanics

* **Standard Yellow Star:** Grants **+1 Point**.
* **Gold Bonus Star:** Grants **+5 Points**.
* **Lives:** You start with **3 Lives**[cite: 1]. Missing a star subtracts 1 life[cite: 1].
* **Progressive Difficulty:** As your score increases, stars spawn at a faster rate to increase the challenge[cite: 1].
* **Game Over:** The game ends when lives drop to 0, displaying your final score with an option to play again[cite: 1].

---

## 🛠️ Features & Technical Highlights

* **Pure Vanilla Architecture:** Built entirely using native HTML5, CSS3, and JavaScript with zero external frameworks or dependencies[cite: 1].
* **Dynamic Canvas Effect:** Dynamic generation of CSS keyframe-animated background stars for an immersive deep-space aesthetic[cite: 1].
* **Real-time Collision Detection:** Utilizes JavaScript bounding rectangle calculations (`getBoundingClientRect`) to detect basket and star collisions accurately[cite: 1].
* **Audio Feedback:** Integrated web audio playback upon successfully catching stars[cite: 1].

---

## 📂 Project Structure

```text
Falling-Star-Game/
├── index.html       # Combined structure, styling, and JavaScript game loop
└── README.md        # Project documentation
