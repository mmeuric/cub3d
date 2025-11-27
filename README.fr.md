# 🧱 cub3D

A 3D maze renderer inspired by *Wolfenstein 3D*, built from scratch using ray-casting.
This project introduced me to graphical programming, vector math, textures, player movement, and real-time rendering using MiniLibX.

I added a screenshot to this repository to illustrate the final in-game result. *(See the image below in the README.)*

---

## 🚀 Features

* Real-time ray-casting engine
* Smooth player movement & rotation
* Wall rendering with directional textures (N, S, E, W)
* Floor & ceiling color management
* Full parsing of `.cub` scene files
* Map validation (closed map, spawn orientation, characters, textures, etc.)
* Clean handling of window events (ESC & red cross)
* Built using **MiniLibX**, **C**, and **math library (-lm)**

---

## ▶️ How to Run

```bash
make
./cub3d map/map.cub
```

---

## 🎮 Controls

| Key     | Action        |
| ------- | ------------- |
| **W**   | Move forward  |
| **S**   | Move backward |
| **A**   | Strafe left   |
| **D**   | Strafe right  |
| **→**   | Turn right    |
| **←**   | Turn left     |
| **ESC** | Quit game     |


---

## 🖼️ Game Preview

Below is a screenshot showcasing the final rendering:

**➡️ *(insert your screenshot file here, e.g. `![cub3d screenshot](screen.png)`)*

---

## 📚 Technologies Used

* **C**
* **MiniLibX**
* **Ray-casting math**
* **Makefile**
* **Matrix & vector operations**

---

## 📝 About the Project

This 42 School project taught me how to:

* Build a simple 3D engine from scratch
* Parse configuration files safely
* Handle graphics, events, and inputs
* Work with low-level rendering and real-time constraints
  
