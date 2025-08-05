🎨 Cyan Window – GLFW + OpenGL
A super simple OpenGL example that opens a window with a cyan background and a custom title:
Razibul Hasan Badhon.
Press R (for "Razibul") or ESC to close the window.

✨ Features
🟦 Cyan background – bright and eye-catching

📝 Custom window title – your name at the top

⌨ Simple controls – press R or ESC to exit

🪶 Minimal & beginner-friendly code

⚙ Build & Run
1. Install dependencies
GLFW – window creation & input

GLAD – OpenGL function loader

2. Build (example with g++)
bash
Copy
Edit
g++ src/main.cpp src/glad.c -o CyanWindow -Iinclude -lglfw3 -lopengl32 -lgdi32
3. Run
bash
Copy
Edit
./CyanWindow
📂 Project Structure
makefile
Copy
Edit
Graphics/
│
├── include/       # Header files (GLFW, GLAD, etc.)
├── src/           # Source files
│   ├── main.cpp   # Entry point
│   └── glad.c     # GLAD loader
└── README.md
📜 License
This project is licensed under the MIT License – feel free to modify and share.
