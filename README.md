# DOCTYPE
DOCTYPE pro lab
# 🧪 Pro Labs | Advanced Virtual Science Interface

Pro Labs is a next-generation interactive physics and chemistry simulation engine contained within a single HTML file[cite: 2]. It features a modern glassmorphism UI, a real-time 3D ambient background, and multiple interactive science modules driven by HTML5 Canvas and JavaScript[cite: 2].

---

## ✨ Features & Modules

The application includes five distinct interactive simulation modules[cite: 2]:

*   **Nuclear (Fission Reactor):** A thermodynamic simulation where users modulate control rod insertion to manage neutron absorption[cite: 2]. Users must balance power output and core temperature to prevent a critical meltdown[cite: 2].
*   **Orbital (Gravity Well):** A Keplerian orbit dynamics simulation[cite: 2]. Users can adjust a central star's mass via a slider and observe the real-time velocity changes in orbiting bodies[cite: 2].
*   **Chemistry (Reaction Chamber):** Simulates the highly exothermic reaction between an alkali metal (Sodium) and water[cite: 2]. Features interactive buttons to introduce reagents, triggering a particle-based explosion effect, along with a chamber purge function[cite: 2].
*   **Optics (Spectral Optics):** Demonstrates prism dispersion and Snell's Law[cite: 2]. Users can adjust the prism's angle of incidence to see how white light disperses into a color spectrum[cite: 2].
*   **Waves (Wave Dynamics):** An interactive fluid simulation[cite: 2]. Users can click on the display to generate ripples and observe constructive and destructive wave interference patterns[cite: 2].

---

## 🛠️ Technology Stack

*   **Core Languages:** HTML5, CSS3 (using CSS Variables and modern layouts), and Vanilla JavaScript[cite: 2].
*   **3D Graphics:** Three.js (r128) is utilized to render the ambient, liquid-glass morphing background using icosahedron geometry and vertex displacement[cite: 2].
*   **Animations:** GSAP (3.12.2) is implemented for smooth, elastic UI crossfade transitions and entrance animations[cite: 2].
*   **2D Simulations:** HTML5 `<canvas>` API is used extensively for rendering the orbits, chemical particle explosions, optical laser beams, and wave ripples[cite: 2].
*   **Assets:** FontAwesome 6.4.0 for UI icons, with Space Grotesk (headers) and Outfit (tech text) fonts loaded via Google Fonts[cite: 2].

---

## 🚀 Getting Started

Because Pro Labs is entirely client-side and relies on CDN links for its libraries, setup is instant[cite: 2].

1.  **Save the Code:** Copy the provided source code and save it as an `index.html` file on your local machine[cite: 2].
2.  **Run the Application:** Open the `index.html` file directly in any modern web browser (Chrome, Firefox, Safari, Edge). No build tools, package managers, or local servers are required to run the simulations[cite: 2].
