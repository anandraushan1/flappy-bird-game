# flappy-bird-game
🐦 Flappy Bird Game (C++ Project)

A console/graphics-based implementation of the classic Flappy Bird game developed using C++, demonstrating strong fundamentals in data structures, game logic, and real-time system design.

🎮 Project Overview

This project recreates the Flappy Bird gameplay using C++, where the player controls a bird navigating through moving obstacles (pipes) without collision.

The goal is to:
👉 Avoid obstacles and achieve the highest possible score.

This project emphasizes logic building and performance, making it a strong demonstration of core programming skills.

🚀 Features
🐦 Gravity-based bird movement
🎮 Keyboard-controlled jump mechanism
🧱 Dynamically generated obstacles (pipes)
💥 Collision detection system
📊 Real-time score tracking
🔁 Game restart functionality
⚡ Fast execution with efficient memory usage
🧠 Core Game Logic (Key Highlight for Recruiters)
1. Game Loop (Core Engine)
Implemented using a loop (while loop)
Continuously updates:
Bird position
Pipe movement
Collision checks
Score updates

👉 Acts as the heartbeat of the game

2. Gravity & Physics Simulation
Bird movement controlled by:
Gravity (constant downward force)
Upward velocity on key press

👉 Logic:

Each frame → bird position updated using velocity
Key press → negative velocity applied (jump)
3. Pipe Generation Algorithm
Pipes generated dynamically with:
Random heights
Fixed gap for movement

👉 Logic:

Pipes move horizontally
New pipes are created as old ones exit screen
4. Collision Detection
Game ends when:
Bird hits pipe
Bird hits ground

👉 Implemented using:

Coordinate-based or boundary checking
5. Score System
Score increases when:
Bird successfully crosses a pipe

👉 Logic:

Track bird position relative to pipe
6. Memory & Performance Optimization
Efficient use of:
Variables and arrays
Minimal memory overhead

👉 Ensures smooth gameplay even in C++

🛠️ Tech Stack
C++ – Core programming & logic
Graphics Library (if used):
SFML / SDL / Console-based rendering (mention what YOU used)
OOP Concepts – Structuring game components
📂 Project Structure
Flappy-Bird-Cpp/
│
├── main.cpp        # Core game logic
├── game.cpp        # Game functions (if applicable)
├── game.h          # Header files
├── /assets         # Images / sounds (if used)
└── README.md
▶️ How to Run
git clone https://github.com/anandraushan1/flappy-bird-game.git
cd flappy-bird-game
g++ main.cpp -o game
./game

(Modify compile command if you used graphics library like SFML)

🎮 Controls
Spacebar / Key Press → Bird jumps
No input → Bird falls due to gravity
💡 What This Project Demonstrates
Strong understanding of:
C++ fundamentals
Game loop architecture
Real-time system logic
Problem-solving & algorithm design
Practical implementation of:
Physics simulation
Collision detection
Dynamic object handling
📌 Future Improvements
Add graphical interface (SFML/SDL) 🎨
Add sound effects 🔊
Implement difficulty scaling 📈
Store high scores using file handling 💾
👨‍💻 Author

Anand Raushan
GitHub: https://github.com/anandraushan1

⭐ Why This Project Matters

This project highlights:

Strong core programming skills in C++
Ability to implement real-time systems from scratch
Deep understanding of logic building and performance optimization





