# CEVI 3D Jewellery Display

This project was built as part of the **CEVI AR Developer Role assessment**.  
It is an interactive Web-based 3D jewellery showcase developed using **A-Frame**, focusing on smooth animations, clean state management, and ECS-based interactions.

---

##  Live Demo
https://coruscating-quokka-a0ab54.netlify.app

##  GitHub Repository
https://github.com/soumya0911/cevi-3d-jewellery-display

---

## Project Overview

The application displays three 3D jewellery rings in a scene.  
Users can click on a ring to focus it, rotate it using drag interaction, and close it to return the ring to its original position.

The implementation emphasizes correctness, smoothness, and robustness rather than visual complexity.

---

##  Tech Stack

- A-Frame (WebGL)
- HTML, CSS, JavaScript
- GLB 3D Models
- Netlify (Deployment)

---

##  Rubric Coverage (CEVI)

###  Core Mechanics & Visual Fidelity
- Smooth focus and return animations with easing
- Correct scaling and UI behavior
- Each ring returns to its own original position
- Dynamic lighting used for realistic metallic appearance

###  State Management & Logic
- Busy state prevents multiple interactions at once
- Input isolation ensures UI actions do not affect the scene
- Full state reset after closing a ring

###  Advanced Interaction (ECS)
- Drag-to-rotate implemented using mouse and touch events
- Rotation is continuous and does not snap
- Rotation resets automatically when the ring is returned

###  Code Quality
- Clear variable naming and readable logic
- Modular interaction logic using custom A-Frame components
- No third-party drag or interaction libraries used

---


