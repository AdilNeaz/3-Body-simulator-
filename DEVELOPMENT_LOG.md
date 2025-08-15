# Development Log — 3‑Body Problem Simulator (5 Weeks)

**Author:** Adil Neaz
**Project:** Interactive Three‑Body Problem Simulator (AU · M☉ · km/s)
**Live demo:** [https://adilneaz.github.io/3-Body-simulator-/](https://adilneaz.github.io/3-Body-simulator-/)
**Repo:** [https://github.com/adilneaz/3-Body-simulator-](https://github.com/adilneaz/3-Body-simulator-)

---

## Weeks 1–3 — Concept Selection, Research & Skill Building

**Focus:** Choosing the project idea, understanding the physics, and learning the technical skills.

* Selected the **three‑body problem** due to its unique combination of astrophysics, chaos theory, and visual complexity.
* Researched its astrophysical applications: stability of planetary systems, star cluster dynamics, and spacecraft trajectory planning.
* Studied **chaos theory fundamentals**, especially sensitivity to initial conditions, and how this manifests in orbital dynamics.
* Installed **Anaconda** and **PyCharm** to experiment with Python-based simulations, testing simple gravitational motion scripts.
* Decided on a **web-based JavaScript + HTML5 Canvas** implementation for real-time visualisation and ease of sharing via browsers.
* Learnt HTML, CSS, and JavaScript basics from MDN Web Docs, focusing on DOM manipulation, event listeners, and Canvas drawing.
* Explored **Newton’s Law of Gravitation** in depth, calculating forces as vector components.
* Understood astronomical units (AU, M☉, km/s), converting them into SI units for calculations while retaining AU/M☉ in the UI.
* Investigated numerical integration techniques — comparing Euler, Verlet, and RK4 — and selected **Runge–Kutta 4th Order** for its stability and accuracy in chaotic systems.
* Passively built foundational knowledge through video tutorials, scientific papers, and small coding exercises.

---

## Week 4 — Core Simulation Architecture & Implementation

**Day 1–8:**

* Designed body objects to store **mass, position, velocity, colour, and trail history**.
* Implemented gravitational force calculation between each body pair, using a **softening factor (ε²)** to prevent singularities in near-collisions.
* Coded the RK4 integration process: calculating k1–k4 slopes for position and velocity, averaging, and applying updates.
* Added UI elements: sliders and numeric fields for **mass**, **position (x/y)**, and **velocity (x/y)** to allow full user control.
* Introduced a **time-speed slider** to simulate days per second, enabling both slow-motion study and fast-forward.
* Developed **pause/play controls** to freeze or resume the simulation loop.

---

## Week 5 — Feature Expansion, Polish, and Deployment

**Day 9–12:**

* Created dynamic trails for each body, fading over time for a realistic motion path representation.
* Implemented velocity-based colour coding, mapping speed magnitudes to a logarithmic colour scale (blue→green→yellow→red).
* Added interactive camera controls: **zoom** via mouse wheel (centered on cursor) and **panning** via right-click drag.
* Built a draggable, real-time **speed legend** showing current velocity ranges.

**Day 13–14:**

* Developed a collapsible **help/info panel** detailing units, controls, chaos theory concepts, and the astrophysical relevance of the three-body problem.
* Made the simulation **pause automatically** when the help panel is open to allow uninterrupted reading.
* Added orbital presets: **Sun–Earth–Jupiter** (stable-ish system), **Binary Star + Probe** (chaotic interactions), and **Figure‑8 orbit** (rare special solution).
* Applied the **MIT License** to the codebase for open-source sharing.
* Published the simulator via **GitHub Pages**, tested across devices, and finalised the README and LICENSE.

---

## Reflection

Over five weeks, I transformed a complex theoretical problem into a functional, interactive educational tool. I strengthened my understanding of orbital mechanics, gravitational dynamics, numerical integration, and chaotic behaviour. I also demonstrated adaptability, starting with Python and shifting to JavaScript for real-time visualisation. This project honed my skills in both **physics** and **software engineering**, preparing me for future academic challenges.
