# The Untouchable Lamp 💡

An interactive, physics-based web toy built purely with HTML, CSS, and HTML5 Canvas. "The Untouchable Lamp" invites you to interact with a delicately simulated environment where you can flip a realistic light switch, or grab a slingshot to shatter the bulb!

## ✨ Features
* **Interactive Physics Engine:** A custom-built 2D physics engine handling gravity, elastic band tension, object collision, and shattering glass particles.
* **Dynamic Canvas Lighting:** Real-time glow, shadows, and flickering effects rendered directly on an HTML5 canvas.
* **Immersive Audio:** Procedurally generated sound effects (using the Web Audio API) for the slingshot twang, light switch clicks, electrical zaps, and breaking glass.
* **Real-time Clock:** Displays the user's actual local time dynamically on the screen.
* **Startup Animation:** A custom electrical flickering intro sequence when the project first loads.
* **Zero Dependencies:** Built entirely with vanilla JavaScript, HTML, and CSS. No frameworks, no external libraries.

## 🚀 How to Run Locally
Since this project consists of static files with no backend dependencies, running it is incredibly simple.

1. Clone or download this repository to your local machine.
2. Open the `index.html` file directly in any modern web browser.
3. *Alternatively*, serve it using a local HTTP server (e.g., `python -m http.server 8080`) and visit `http://localhost:8080`.

## 🎮 How to Play
- **The Wall Switch:** Click (or press Space/Enter) the switch on the right side of the screen to turn the lamp on or off. 
- **The Slingshot:** Click and drag the slingshot pouch at the bottom of the screen. Aim for the lamp shade to make it swing, or hit the bulb to shatter it.
- **The Lamp Shade:** You can click and drag the lamp shade directly to swing it back and forth.
- **Reset:** If you break the bulb, a "replace bulb" button will appear (or press 'R' on your keyboard).

## 🛠️ Technologies Used
- HTML5
- CSS3 (Custom properties, animations, gradients)
- Vanilla JavaScript (ES6+)
- HTML5 `<canvas>` API
- Web Audio API

## 📝 License
This project is open-source and available for educational and recreational purposes.
