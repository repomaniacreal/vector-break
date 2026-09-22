# 🎮 Vector Break

**Vector Break** is a fast-paced retro arcade game inspired by classic **Breakout** and **Arkanoid** games.

Control the paddle, bounce the ball, destroy blocks, collect power-ups, and try to achieve the highest score possible.

The game is built entirely with **HTML, CSS, and JavaScript** and runs directly in a modern web browser.

## ✨ Features

* 🧱 Classic block-breaking gameplay
* 🏓 Player-controlled paddle
* ⚡ Real-time ball physics and collision detection
* 💥 Block destruction effects
* 🎁 Random power-ups
* 🔫 Laser power-up
* 🔵 Duplicate Ball power-up
* 🎯 Increasing power-up frequency
* 🕹️ Retro arcade-inspired visual style
* 📱 Browser-based gameplay
* 🚫 No backend or database required
* ⚙️ No external dependencies

## 🛠️ Built With

* **HTML5** — Game structure
* **CSS3** — Visual design, effects, and animations
* **JavaScript** — Game logic, physics, collision detection, scoring, and power-ups

## 📂 Project Structure

```text
vector-break/
│
├── index.html
└── README.md
```

The entire game is contained in `index.html`.

No additional installation or dependency setup is required.

## 🚀 Getting Started

### Option 1 — Run Locally

Clone the repository:

```bash
git clone https://github.com/USERNAME/vector-break.git
```

Navigate into the project directory:

```bash
cd vector-break
```

Open `index.html` in your browser.

That's it!

### Option 2 — Run with a Local Server

You can also use a simple local HTTP server.

With Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## 🎮 How to Play

The goal is simple:

> **Destroy all the blocks without letting the ball fall below your paddle.**

Move the paddle to keep the ball in play and destroy as many blocks as possible.

### Controls

| Input     | Action                               |
| --------- | ------------------------------------ |
| `←` / `A` | Move paddle left                     |
| `→` / `D` | Move paddle right                    |
| `Space`   | Start / continue the game            |
| Mouse     | Move the paddle                      |
| Touch     | Control the paddle on mobile devices |

## 🎁 Power-Ups

Power-ups can appear when blocks are destroyed.

### 🔫 Laser

The **Laser** power-up gives the paddle the ability to fire projectiles at blocks.

Use it to quickly clear multiple blocks from the arena.

### 🔵 Duplicate Ball

The **Duplicate Ball** power-up creates additional balls.

More balls mean more opportunities to destroy blocks and increase your score
