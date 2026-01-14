# 🎯 AR-Gesture-Shooter
A high-octane, browser-based 3D shooting game where your hand is the controller. Using advanced Computer Vision, this project transforms your webcam into a motion-tracking sensor, allowing you to aim and shoot at neon targets using natural hand gestures.
.

🚀 Key Features
AI Hand Tracking: Powered by MediaPipe Hands, detecting real-time coordinates for aiming and gesture triggers.

Pistol Gesture Controls: * Aim: Point your index finger to move the crosshair.

Shoot: Pinch your thumb and index finger together (Trigger Pull) to fire projectiles.

Magnetic Aim Assist: Includes a "snapping" algorithm that helps the crosshair lock onto targets when you are aiming close to them.

Cyberpunk Visuals: Built with Three.js featuring:

UnrealBloomPass for a glowing neon aesthetic.

Dynamic 3D disc enemies with randomized movement patterns.

Floating text VFX (HIT/MISS) and procedural laser lines.

Web Audio Integration: Immersive spatial sound effects for hits and misses using the Web Audio API.

Responsive UI: A retro "Press Start 2P" arcade-style HUD and a fully responsive 3D canvas.

🛠️ Tech Stack
Engine: Three.js (WebGL)

AI/ML: MediaPipe Hands

Frontend: HTML5, CSS3 (Flexbox, Animations), JavaScript (ES6+ Modules)

Post-Processing: EffectComposer (Bloom/Glow effects)

🎮 How to Play
Allow Webcam Access: The game requires your camera to track hand movements.

The Gesture: Form a "pistol" shape with your hand.

Extend your index finger to aim the laser.

Bring your thumb close to your index finger to shoot.

Objective: Destroy the incoming neon discs before they pass your screen. Each hit grants 10 points.

Pause: Press 'P', 'Escape', or click the on-screen button to pause the action.

🔧 Installation & Setup
Since this project uses ES6 modules and MediaPipe CDN, it is recommended to run it via a local server to avoid CORS issues:

Clone the repository:
git clone https://github.com/rishabhkothiyal1/ar-gesture-shooter.git
Open the folder in VS Code.

Use the Live Server extension to launch index.html.

Ensure you have a working webcam and a well-lit environment for the best tracking accuracy.
