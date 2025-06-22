# 🎮 Games_Using_SDL2

This repository includes all the games made using **SDL2 (Simple DirectMedia Layer 2)**.

---

## 🛠️ Installation

1. Install external C libraries:
   - `SDL2`
   - `SDL2_image`
   - `SDL2_ttf`

2. Use your system’s package manager to install the libraries:
   - **Linux Users (Arch-based):**
     ```bash
     sudo pacman -S SDL2 SDL2_image SDL2_ttf
     ```
   - **Windows Users:**
     - Use the **MSYS2** distribution of **MinGW** (it provides an Arch-like subsystem).
     - Then follow the Linux installation method inside the MSYS2 terminal.
     - [Video Link For Installation Part1 ](https://www.youtube.com/watch?v=qH-9UAsI9h8&ab_channel=AtoZProgrammingTutorials)
     - [Video Link For Installation Part2 ](https://www.youtube.com/watch?v=GVMrllOh44U)

3. Compile your C code with proper linking:
   - **For Tic Tac Toe (Terminal):**
     ```bash
     gcc -lSDL2 -lSDL2_image Code_Name.c -o Code_Name
     ./Code_Name
     ```
   - **For 2D Platformer (Terminal):**
     ```bash
     gcc -lSDL2 -lSDL2_ttf Code_Name.c -o Code_Name
     ./Code_Name
     ```

---

## 🙌 Built With ❤️ By

- [Utsav Gupta](https://github.com/Utsav-X-bit/)
- [Ronak Gupta](https://github.com/ronakgupta03)
- [Bhavya Gupta](https://github.com/CodebhavyaG)

