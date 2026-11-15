# 🚀 Space Odyssey: Learn Space Engineering by Doing

> Space Odyssey is an interactive learning platform that teaches space science through hands-on play. Students build rockets, launch satellites, and plan real space missions, learning how each decision affects the outcome.

**Team:** ODESSEYY
**Demo video:** https://youtu.be/5cPAPZkLiV8?si=k8pkvu2rGMDcORAf

---

## Table of Contents

1. [The Problem](#the-problem)
2. [Our Solution](#our-solution)
3. [What's Included](#whats-included)
4. [Key Features](#key-features)
5. [How to Run](#how-to-run)
6. [How to Use](#how-to-use)
7. [Technology](#technology)
8. [Learning Outcomes](#learning-outcomes)
9. [Accessibility and Privacy](#accessibility-and-privacy)
10. [Roadmap](#roadmap)
---

## The Problem

**Challenge: Space Mission Design Game**
## Problem Statement

Space mission design involves complex engineering decisions and trade-offs between mission objectives, spacecraft components, launch vehicles, budgets, mass, power, communication, and orbital constraints. Students often lack opportunities to explore these real-world challenges practically. There is a need for an interactive, engaging platform where students can design, simulate, and manage space missions while learning engineering concepts through experimentation and teamwork.

## Our Solution

Space Odyssey is a learning platform that turns space engineering into hands-on play:

- **Beginner Space Academy** (`odyssey_beginner.html`) is an interactive academy for young learners. Students build rockets, launch satellites, deflect asteroids and rescue astronauts, and learn the physics behind each action as they go.
- **ODESSEYY Advanced Mission Operations** (`odyssey_advanced.html`) is a mission-design simulator for older students. Players take on the role of a NASA-style mission design team, choose a real mission profile, and make engineering trade-offs in a 3D environment.

---

## What's Included

| File | Audience | Description |
|------|----------|-------------|
| `odyssey_beginner.html` | Young learners | Beginner Space Academy with five interactive space games, a science explainer and "Ask the Scientist" |
| `odyssey_advanced.html` | Older students and enthusiasts | ODESSEYY mission simulator built around NASA missions, with a 3D hologram, live telemetry and hand-gesture control |

---

## Key Features

### Beginner Space Academy

- **Welcome screen and nickname:** students enter an optional name and start their journey.
- **Academy home:** a card-based mission hub with a clear navigation structure and Back buttons.
- **Five interactive games:**
  - **Rocket Builder and Launch Simulator:** drag components onto a rocket within a budget, run a pre-launch check, count down and fly a multi-stage launch. Covers rocket parts, Newton's Third Law, staging and cost versus performance.
  - **Mission to Orbit: Newton's Cannon:** choose speed, height and direction, then watch gravity bend the path into an orbit or a crash. Covers gravity, inertia, orbits and escape velocity.
  - **Satellite Design and Deployment Lab:** design a satellite for a mission and deploy it. Covers power, communication and thermal control.
  - **Asteroid Belt Defender:** pilot a planetary defence interceptor, dodge space rocks and blast incoming asteroids. Covers momentum and laser targeting.
  - **Jet-Pack Rescue and Exoplanet Lander:** rescue a stranded astronaut and land on an exoplanet, using jet-pack controls and a rescue checklist.
- **Ask the Scientist:** a conversational helper that answers space questions aloud, with optional voice input.
- **Progress and achievements:** progress is saved in the browser, with badges for milestones such as "First Successful Launch" and "Satellite Scientist".
- **Mission certificate:** students who complete the missions can earn a certificate.
- **Sound toggle:** sound can be turned on or off from the header.

### ODESSEYY Advanced Mission Operations

- **Commander Nova briefing:** a mission-control intro that frames every choice as an engineering trade-off.
- **Six-phase mission flow:**
  1. **Planning:** choose a mission objective (Artemis I, NASA PACE or Mars 2020 Perseverance) and read the briefing.
  2. **Flight plan:** set the target orbit and trajectory, and check mission constraints.
  3. **Vehicle:** choose a launch vehicle (for example SLS, Falcon Heavy or Falcon 9) and configure the crew module and payload.
  4. **Hologram lab:** inspect the spacecraft in a 3D hologram view.
  5. **Mission operations:** calculate the orbital insertion burn, deploy the science payload in the right order and respond to an in-flight anomaly.
  6. **Debrief:** review the design and see how decisions shaped the outcome.
- **Resource allocation:** balance mass, power and budget, starting from 100 mission credits.
- **Live telemetry:** engineering diagnostics update as decisions are made.
- **Hand-gesture control:** pinch your thumb and index finger to select and drag, using a webcam.
- **Clear educational framing:** NASA mission facts are presented with references, and gameplay values are labelled as simplified.

---

## How to Run

No build step, server or installation is needed.

1. Download or clone this repository.
2. Open the file you want in a modern browser:
   - `odyssey_beginner.html` for the beginner academy
   - `odyssey_advanced.html` for the advanced simulator
3. Allow microphone access if you want to use voice features, or camera access for hand-gesture control in the advanced simulator.

## Requirements
- Modern browser (Chrome or Edge recommended).
- Internet connection required on first load for external libraries and fonts.
- For camera/microphone permission issues, run locally using `python -m http.server 8000` and open `http://localhost:8000/odyssey_beginner.html`.

## How to Play
**Beginner Academy**
1. Open `odyssey_beginner.html` and enter a nickname.
2. Click **Enter Academy**.
3. Select a mission and click **Start Game**.

**Advanced Mission Operations**
1. Open `odyssey_advanced.html`.
2. Click **I'm Ready** and select a mission.
3. Complete all six mission phases.
4. Review your final debrief.

## Technology Stack
HTML5, CSS3, Vanilla JavaScript, Three.js, MediaPipe Hands, Web Speech API, Google Fonts and Local Storage.

## Learning Outcomes
- Understand rocket staging, thrust and mass.
- Explore orbital mechanics and gravity.
- Learn spacecraft design trade-offs.
- Understand satellite power, communication and thermal systems.

## Privacy & Accessibility
- No installation, account or sign-in required.
- Progress is stored locally in the browser.
- Camera and microphone permissions are optional.
- Educational values are clearly labelled.

## Future Scope
- More advanced missions.
- Teacher dashboard and certificates.
- Multilingual support.
- Improved offline functionality.
- Enhanced accessibility options.
---

## Images 

<img width="1867" height="822" alt="Screenshot 2026-11-15 161522" src="https://github.com/user-attachments/assets/98088e1a-7ca2-4cb0-9227-997d09c8c943" />

<img width="1842" height="876" alt="Screenshot 2026-11-15 161554" src="https://github.com/user-attachments/assets/04ebd889-cebb-42ef-a8e8-571f11fcd120" />

<img width="1616" height="867" alt="image" src="https://github.com/user-attachments/assets/acdbeac2-f511-4ac2-97ea-45fb74782e59" />



## Acknowledgements

- NASA for the publicly available mission information for Artemis I, PACE and Mars 2020 Perseverance.
- The open-source communities behind Three.js, MediaPipe and the Web Speech API.

---

*Learning space science should be an adventure.* 🌌
