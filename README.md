# Two Dot Game (OpenGL)
---

## 🎮 About the Game

A retro-styled arcade game built with OpenGL and GLUT, where the player controls a dot to collect food within a time limit. Each successful collection extends playtime, while failure to collect within 500 ms ends the game. Colliding with obstacles, walls, or exceeding the time limit ends the session.

---

## 🛠️ Features

- Real-time rendering of player, food, walls, and obstacles  
- Keyboard input handling via **W/A/S/D** for directional movement  
- Time-limited gameplay: collect food every 500 ms to continue  
- Score tracking and display  
- Game over on collision or time-out, with final score shown
- 
#### Game View

![Image](https://github.com/user-attachments/assets/ace5b6a4-f989-4800-af14-031ea1affa45)

---

## 🧩 Requirements

- **C++** compiler  
- **CodeBlocks** IDE (configured with OpenGL/GLUT)  
- OpenGL libraries: `glut`, `GLU`, `GL`  
- Platform: Windows (uses `<windows.h>`, `sndPlaySound` for audio playback)

---

## 🚀 Setup & Run

1. Clone the repository:
   ```bash
   git clone https://github.com/devjohurul/Two-Dot-Game-OpenGL.git
   cd Two-Dot-Game-OpenGL
