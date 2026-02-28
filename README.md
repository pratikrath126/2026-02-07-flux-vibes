
# Flux Vibes - Real-time Audio Visualizer

**Flux Vibes** is an interactive, web-based audiovisual experience that transforms ambient sound from your microphone into mesmerizing, real-time generative art. It uses the Web Audio API to capture and analyze sound, and the HTML5 Canvas to render a dynamic particle system that dances to the rhythm of your voice, music, or any surrounding noise.

## 🚀 Live Demo

A live demo is available at [https://flux-vibes.onrender.com](https://flux-vibes.onrender.com).

## ✨ Features

- **Real-time Audio Analysis:** Captures microphone input and analyzes frequency data on the fly.
- **Dynamic Particle System:** Features thousands of particles that react to sound intensity, creating a "flux" effect.
- **Interactive Mouse/Touch Controls:** The particle cloud is repelled by your cursor or finger, allowing you to "play" with the visualization.
- **Generative Connections:** As particles get closer, they form ethereal connections, with the brightness and frequency of these connections influenced by the audio input.
- **Stunning Visuals:** A sleek, dark, futuristic UI with neon and glow effects for a polished look.
- **No Dependencies:** Built with vanilla HTML, CSS, and JavaScript. No external libraries are needed.
- **Responsive Design:** Adapts to any screen size, from mobile phones to desktops.

## 🛠️ How It Works

The application is built with three core components:

1.  **HTML (`index.html`):** The main structure of the web page, including the canvas for the visualization and the UI elements.
2.  **CSS (Embedded):** Provides the styling for the page, creating the dark, futuristic theme with glowing elements and a blurred background effect.
3.  **JavaScript (Embedded):**
    *   **Web Audio API:** Accesses the user's microphone, creates an `AudioContext`, and uses an `AnalyserNode` to extract real-time frequency data from the audio stream.
    *   **Canvas API:** Renders the particles and their connections. The script updates the position and appearance of each particle on every frame based on both the audio data and user interaction.
    *   **Particle Class:** A simple class defines the behavior of each particle, including its position, velocity, and how it responds to external forces like sound and mouse movement.

## Usage

1.  Open the `index.html` file in a modern web browser (Chrome, Firefox, Safari, Edge).
2.  Click the **"Start Visualization"** button.
3.  Your browser will prompt you for microphone access. **Allow** it.
4.  Speak, play music, or make some noise! Watch the particles react in real-time.
5.  Move your mouse over the canvas or touch the screen to interact with the particle field.

---
*This project was created by the OpenClaw AI assistant as part of the "Project Green" automation initiative.*
