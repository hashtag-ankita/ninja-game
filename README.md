# 🥷 Ninja Game – Pygame OOP Project

> A side-scrolling ninja platformer game built using **Pygame** with **object-oriented programming**. This project is part of my learning journey — updated daily to track progress and build habits.

---

## 🎥 Current Gameplay

*(Player movement, idle, run, and jump animation demo)*

![Player Movement Demo](demo.gif)

---

## 🚧 Progress Log

### 📅 Day 1 – *\[2025-07-15]*

* Created the `Game()` class to manage the main game loop.
* Set up the game window (`640x480`) and background.
* Set the window title to "Ninja Game".
* Added basic quit functionality (close button works).
* Frame rate limited to 60 FPS using `pygame.time.Clock()`.

---

### 📅 Day 2 – *\[2025-07-19]*

* Created a `PhysicsEntity` object to represent the player and handle horizontal movement (no animation yet).
* Implemented **gravity physics** with gradual acceleration up to a cap.
* Added a utility function to **load a single image**.
* Introduced a `data/` folder to store all images and assets.

---

### 📅 Day 3 – *\[2025-07-20]*

* Added `tilemap.py` and implemented a `Tilemap` class for handling different tile types.
* Wrote a utility function to **load and return images as lists**.
* Rendered tiles on screen (initial rendering for learning purposes; not final visuals).

---

### 📅 Day 4 – *\[2025-07-21]*

* Implemented **collision detection** and **player jumping**.
* Used collision detection to ensure the player stands on the ground instead of passing through it.
* Tweaked gravity: acceleration resets to `0` upon ground collision and ramps up again when falling.

---

### 📅 Day 5 – *\[2025-07-22]*

* Implemented **camera movement** relative to the player.
* Added a **background image**.
* Added **clouds** with parallax-style depth, movement, and looping for a more dynamic sky.

---

### 📅 Day 6 – *\[2025-07-23]*

* Optimized tile rendering (only drawing what’s needed / prepping for culling off-screen tiles).

---

### 📅 Day 7 – *\[2025-07-27]*

* Added **player animation** for idle, run, and jump states.
* Implemented **flipped animation** when the player faces left/right.
* Created a **`Player` object** inheriting from `PhysicsEntity`, with player-specific settings.

---

## 📌 Notes

This log will continue to grow with each day’s progress.
