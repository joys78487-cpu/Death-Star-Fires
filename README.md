# 🌌 Death Star Fires – Interactive Canvas Simulation

A cinematic browser-based animation recreating the destruction of Alderaan from
**Star Wars: Episode IV – A New Hope**.

This project uses pure **HTML5 Canvas + JavaScript** to simulate the iconic moment when the **Death Star** fires its superlaser and annihilates **Alderaan**.

No libraries. No frameworks. Just raw canvas power.

---

## 🚀 Overview

This animation features:

* ⭐ Moving starfield background (space travel feel)
* 🛰️ Fully rendered Death Star
* 🌍 Alderaan planet model
* 💚 Charging superlaser beam animation
* 💥 Expanding explosion effect
* 🌊 Shockwave ring
* 🔥 Debris fragments
* 🔴 Red flash overlay
* 📳 Screen shake effect
* 🎛️ Interactive UI buttons

The sequence follows this flow:

`Idle → Charge → Beam Fires → Explosion → Shockwave → Planet Destroyed`

---

## 🎮 Controls

| Button              | Action                                                |
| ------------------- | ----------------------------------------------------- |
| **Fire Death Star** | Begins the charging sequence and fires the superlaser |
| **Reset**           | Resets the entire scene to idle state                 |

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla)**
* **Canvas API**

No external dependencies required.

---

## 🎬 What Happens Behind the Scenes

### 🌠 Starfield

* 400 stars generated randomly
* Continuous leftward movement
* Stars reset when exiting the screen

### 🛰️ Death Star

* Positioned left-center
* Drawn using layered circles
* Includes concave dish detail
* Responsive scaling based on screen size

### 🌍 Alderaan

* Positioned right side
* Scales dynamically with screen width
* Disappears after destruction

### 💚 Superlaser Beam

* Progressive beam animation using `beamProgress`
* Glowing effect using `shadowBlur`
* Responsive beam width

### 💥 Explosion

* Expanding orange circle
* Radius increases each frame
* Triggers debris + shockwave

### 🌊 Shockwave

* Expanding white ring
* Slightly slower growth than explosion core

### 🔥 Debris System

* 35 fragments
* Random velocity vectors
* Particle-style outward motion

### 🔴 Red Flash

* Full-screen overlay
* Gradual fade-out

### 📳 Screen Shake

* Random canvas translation
* Intensity decays over time

---

## 📐 Responsive Design

The canvas automatically adjusts to:

* Window resizing
* Different screen resolutions
* Mobile or desktop viewports

All object sizes scale proportionally using `canvas.width`.

---

## ▶️ How to Run

1. Copy the HTML code into a file

   ```
   deathstar.html
   ```
2. Open it in any modern browser:

   * Chrome
   * Edge
   * Firefox
   * Safari

No server required.

---

## 🧠 Educational Value

This project demonstrates:

* Canvas rendering loops
* Particle systems
* Animation state management
* Responsive scaling
* Basic game-style phase control
* Visual effects layering

Perfect for learning animation logic without game engines.

---

## 🌟 Possible Enhancements

If you want to push it further:

* Add sound effects (laser + explosion)
* Add charging glow animation on the Death Star
* Add multiple planets
* Add cinematic zoom-in before firing
* Add star warp effect during charge
* Add Imperial UI overlay styling

---

## 📜 License

This project is a fan-made tribute inspired by
**Star Wars: Episode IV – A New Hope**.

All Star Wars characters and concepts belong to
**Lucasfilm Ltd.** and
**The Walt Disney Company**.

This code is for educational and non-commercial purposes only.

---

## 👨‍💻 Author Note

Created for fans who love coding and cinematic sci-fi moments.
If you enjoy building interactive space simulations — this is your starting point.

May the Force be with you. ✨
