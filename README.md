# Boba-Boxing-Club-P5.JS-Code-Game
The Web Documentation: https://ayu26-cpu.github.io/boba-game/
The Coded Game: https://editor.p5js.org/Ayu26-cpu/sketches/pHAU9FVrG
Boba Boxing Club - Interactive p5.js UX Engineering & Logic Sandbox

📋 Project Overview
Boba Boxing Club is a real-time, canvas-based interactive web application built using the p5.js library. While it functions as a playable game, this repository serves as a practical testing sandbox for front-end interface behavior, responsive design, and visual accessibility. 

The main goal was to build a fast-paced interactive canvas while ensuring the controls feel completely responsive, the interface elements are easy to read, and the system design remains fair and accessible to all users.

---

## 🔬 Frontend Testing & Interface Design Principles Applied
The code logic and layout rendering for this application were structured and audited using standard human-computer interaction (HCI) and digital design practices:

### 1. Real-Time Interface Feedback & Input Handling
To keep the application highly responsive during fast interactions, the code ensures the screen always reflects the current background logic instantly:
* **Clear Interface Status Updates:** Programmed real-time visual indicators (like stamina meters, action cooldown timers, and changing score values) that give users instant updates on their current interaction state.
* **Responsive Control Validation:** Configured immediate visual feedback frames right when keys are pressed. When a user acts, the canvas updates immediately so inputs never feel delayed or unresponsive.
* **Control Safeguards:** Structured the underlying logic loops to handle rapid, repetitive button presses smoothly, preventing the code from skipping cooldown rules or getting stuck between rapid state transitions.

### 2. Fair Design & Avoiding Manipulative Mechanics
Following standard user advocacy and ethical design practices, the game loops were written to avoid frustrating or deceptive interface traps:
* **Respecting User Autonomy:** The interface is built without hidden mechanics, stressful timers, or artificial pressure traps, ensuring a transparent experience where the user has clear control and clean exit paths.
* **Reducing Screen Fatigue:** Avoided chaotic, flashing elements or messy layouts that cause eye strain, keeping the interface focused entirely on intentional interactive goals.

### 3. Accessible Layouts & Visual Hierarchy
To make sure the canvas elements are easily readable for a wider range of users, the layout choices were checked against standard web accessibility concepts:
* **Color Contrast & Readability:** Evaluated color palettes to ensure text and active targets remain distinct, specifically choosing combinations that are readable for users with common color-vision deficiencies like **Protanopia** and **Deuteranopia**.
* **Clean Spatial Layout:** Designed a clear focal pathway on the canvas, keeping essential metrics, textual indicators, and moving targets visually separated so the player never loses track of the action.

## 🛠️ Logic Verification & Quality Assurance Sandbox Tasks
To guarantee functional stability, the script compilation was run through manual QA testing cycles:
* **Boundary Parameter Analysis:** Tested interaction collision zones at maximum and minimum spatial borders to ensure coordinate math prevents asset Clipping or boundary dropouts.
* **Input Stress Testing:** Simulated extreme button saturation to verify state-machine calculation stability and prevent frame-rate execution crashes.
