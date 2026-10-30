# Game Development Resume

This folder contains a tailored resume designed specifically for **Game Development / Gameplay & Systems Engineering** roles.

## Design Goals
- **Code & Game Engine Agnostic**: Focuses on core game engineering principles (Component-Based Architecture, Finite State Machines, 3D Vector Math & Linear Algebra, Rigid-Body Dynamics, Kinematics, Object Pooling, Input Buffering, and Profiling) rather than tying expertise to a single engine or language.
- **Engine & Language Breadth**: Showcases shipped projects and interactive systems built across **C++, C#, GDScript, TypeScript, Python, GLSL**, utilizing **Unity, Godot, Three.js/WebGL**, and **Custom Systems**.
- **Portfolio-Aligned**: Directly reflects projects and experiences from `sebastiandleon.dev`, including the WMU Hackathon Winner (*Ying Yang Cats*), NASA HERC 1st Place Rover and Simulator, *Marine Guardians*, *Printune*, and co-founding the *DreamBytes Game Dev Club*.
- **Single-Page Optimization**: Formatted with precise LaTeX geometry and typography to fit onto a single page.

## Structure
- `resume.tex`: Master LaTeX document.
- `glyphtounicode.tex`: Character mapping for ATS readability.
- `sections/`:
  - `summary.tex`: High-impact game engineering profile.
  - `skills.tex`: Taxonomy organized by architecture, math/physics, languages, engines, and tools.
  - `projects.tex`: Flagship game and interactive simulation projects.
  - `experience.tex`: Professional interactive systems development, game outreach, and club leadership.
  - `education.tex`: Western Michigan University and INTEC academic history and honors.

## Compiling to PDF
Run the following command from this directory:
```powershell
pdflatex -interaction=nonstopmode resume.tex
```
