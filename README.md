# 🎮 Browser Games

A curated collection of nostalgic, interactive, physics-based games designed to run directly in any web browser with zero external dependencies.

---

## 🌊 Game 1: 3D Water Ring Toss Handheld Toy

A faithful digital recreation of the iconic retro handheld water ring toss toy ([YouTube Video Reference](https://www.youtube.com/watch?v=YpFm_tH28sY)).

![Water Ring Toss](https://img.shields.io/badge/Physics-Hydrodynamic%20Simulation-00c6ff)
![HTML5 Canvas](https://img.shields.io/badge/Platform-HTML5%20%2F%20Canvas-ff3366)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-None%20(Pure%20JS)-06d6a0)

---

## 🚀 How to Play

### Option A: Play Online Instantly (GitHub Pages)

You can play the game right in your browser without downloading anything!

1. **Direct Link:**  
   👉 **[https://bgtsidharth.github.io/Browser-Games/](https://bgtsidharth.github.io/Browser-Games/)**  
   *(Or [`https://bgtsidharth.github.io/Browser-Games/water-ring-toss/`](https://bgtsidharth.github.io/Browser-Games/water-ring-toss/))*

> **Note for Repository Owner:**  
> To enable GitHub Pages:  
> 1. Go to your repo **Settings** on GitHub.  
> 2. Scroll to the **Pages** section on the left sidebar.  
> 3. Under **Branch**, select `main` and root `/` folder, then click **Save**.  
> 4. The game will be live worldwide in ~1 minute!

---

### Option B: Play Locally on Your Computer

No installation, Node.js, or web server required!

1. **Clone or Download the Repository:**
   ```bash
   git clone https://github.com/bgtsidharth/Browser-Games.git
   ```
   *(Or click **Code > Download ZIP** on GitHub and unzip it).*

2. **Open the Game:**
   - Double-click **[`water-ring-toss/index.html`](water-ring-toss/index.html)** in your file explorer.
   - It will immediately open and run in any web browser (Chrome, Edge, Firefox, Safari).

---

## 🕹️ Controls & Mechanics

| Action | Mouse / Touch | Keyboard Shortcut |
| :--- | :--- | :--- |
| **Left Jet Pump** | Click / Tap Left Yellow Button | <kbd>A</kbd> or <kbd>◄ Left Arrow</kbd> |
| **Right Jet Pump** | Click / Tap Right Yellow Button | <kbd>D</kbd> or <kbd>► Right Arrow</kbd> |
| **Tilt / Shake Toy** | Click Center <kbd>📳</kbd> Button | <kbd>T</kbd> or <kbd>Space</kbd> |
| **Scatter / Reset Rings** | Click **"🔄 Shake / Reset"** | <kbd>R</kbd> |

> 💡 **Tip:** Tap the pump buttons in short, rhythmic bursts just like squeezing the physical rubber bulbs on the toy! A sustained hold will decay the squeeze volume naturally.

---

## ✨ Features & Physics Highlights

- **Authentic Buoyant Hydrodynamics:** Lightweight plastic rings float and sink gently in water ($g_{\text{eff}} = 0.065$) with natural falling-leaf flutter and viscous drag.
- **Physical Rubber Bellows Puffs:** Push buttons deliver realistic fluid impulses that shoot bubble trails up outer nozzles, curling over the top and cascading through the center.
- **Solid Rod Deflections & Hooking:** Rings bounce off the solid golden rod shafts from the side. When falling onto the tip, rings with aligned holes slip on and slide down to stack, while off-center hits deflect off the tip.
- **True 3D Toroidal Rendering:** Rings feature 3D donut geometry, ambient drop shadows on the tank backplate, tubular volume lighting, and physical front/back rod-threading layers.
- **Custom Device Skins:** Choose between **💖 Pink Phone**, **🌊 Ocean Aqua**, **🔮 Retro Lilac**, **⭐ Sunshine Yellow**, and **👾 Cyber Neon**.
- **Mobile Accelerometer Support:** Tilt your smartphone to tilt the water tank using device gyroscope sensors.