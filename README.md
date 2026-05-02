# 🏓 Ping Pong Game (x86 Assembly)

A **console-based Ping Pong game** developed in **x86 Assembly Language**, demonstrating low-level programming concepts such as **interrupt handling, memory manipulation, graphics using text mode, and real-time input processing**.

---

## 🚀 Features

### 🎮 Gameplay

* Two-player Ping Pong game
* Real-time ball movement
* Paddle control for both players
* Score tracking system
* Winning condition with restart/exit option

---

### 🎯 Controls

| Player            | Controls                         |
| ----------------- | -------------------------------- |
| Player 1          | `W` (Up), `S` (Down)             |
| Player 2          | `↑` (Arrow Up), `↓` (Arrow Down) |
| Pause/Resume      | `P`                              |
| Change Background | `B`                              |
| Restart Game      | `R`                              |
| Exit Game         | `E`                              |

---

### 🧠 Core Functionalities

* Ball movement with velocity control
* Collision detection:

  * Walls
  * Paddles
* Dynamic background patterns
* Pause/Resume system
* Score display at top of screen
* Winning logic (first to 5 points)

---

## 🛠️ Technologies Used

* **x86 Assembly Language**
* **BIOS Interrupts (INT 16h, INT 21h)**
* **Text Mode Graphics (0xB800 memory)**

---

## 🧩 Concepts Implemented

* Low-level memory addressing
* Keyboard interrupt handling
* Game loop design
* Collision detection logic
* State management (pause, restart)
* Procedural programming in Assembly

---

## 📂 File Structure

```id="f7j2ka"
pingpong.asm   # Main source code
```

---

## ⚙️ How to Run

### Step 1: Install Emulator / Assembler

* DOSBox + TASM / MASM (recommended)

### Step 2: Compile

```bash id="k92mqp"
tasm pingpong.asm
tlink pingpong.obj
```

### Step 3: Run

```bash id="c4n8ds"
pingpong.exe
```

---

## 🖥️ Game Flow

1. Welcome screen with team details
2. Instructions display
3. Press **Enter** to start
4. Game loop begins:

   * Move paddles
   * Ball updates
   * Score updates
5. First player to reach **5 points wins**
6. Option to:

   * Restart (`R`)
   * Exit (`E`)

---

## 🎨 Special Features

* 🟣 Colored UI using text mode memory
* 🌈 Dynamic background patterns
* ⏸ Pause/Resume functionality
* 🔄 Restart system without exiting program

---

## 👩‍💻 Authors

* **Faryal Jafferi** (23F-0606)
* **Rida Mehmood** (23F-0554)

---

## 🎯 Learning Outcomes

* Understanding **Assembly-level game development**
* Working with **hardware interrupts**
* Managing **real-time user input**
* Implementing **graphics in text mode**
* Building a **complete game loop from scratch**

---

## 📌 Future Improvements

* Add sound effects
* Increase difficulty levels
* Add AI (single-player mode)
* Improve graphics (pixel-based mode)
* Add timer-based speed increase

