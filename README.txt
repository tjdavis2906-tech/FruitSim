FruitSim v0.1.1 — Browser Test Chamber

HOW TO RUN ON YOUR CHROMEBOOK
1. Extract this ZIP.
2. Open index.html in Chrome.
3. Click/tap anywhere in the chamber to move the FOOD target.
4. Reset/Pause are in the top-left panel.

No Python, Linux, Replit, npm, pip, or web server is required.

WHAT THIS VERSION DOES
- Draws a lightweight pseudo-3D/grid test chamber in a normal HTML canvas.
- Runs the small real-connectome-derived network from FruitSim v0.0.3 in JavaScript.
- Feeds environment/food-direction values into selected neurons.
- Reads selected downstream activity to influence fly movement.

SCIENTIFIC LIMITATION
The included neuron IDs and listed connectivity counts are real MaleCNS-derived
data from our v0.0.3 extract. The sensor-to-neuron mapping, motor readout,
thresholds, timing, and neural dynamics are experimental FruitSim mappings and
are NOT claimed to reproduce biological fruit-fly behavior.

This is deliberately dependency-free so it works by double-clicking index.html.
A later version can move to true WebGL/Three.js once we have a convenient host.


v0.1.1: Mobile HUD now moves to the bottom and can be collapsed with the +/- button.
