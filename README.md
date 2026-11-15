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

**Requirements**

- A modern browser. **Google Chrome or Microsoft Edge is recommended**, because the voice and gesture features rely on browser APIs that are best supported there.
- An internet connection on first load, because the files load Three.js, MediaPipe and Google Fonts from public CDNs.

**Optional: serve locally**

If you see a microphone or camera permission error when opening the file directly from your computer, serve the folder with a local web server instead:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000/odyssey_beginner.html
```

---

## How to Use

**Beginner Space Academy**

1. Open `odyssey_beginner.html` and enter a nickname (optional).
2. Press **Enter Academy** to reach the academy home.
3. Choose a mission card and press **Start Game**.
4. Use the **← Back** button in the header to return to the previous page at any time.

**ODESSEYY Advanced Mission Operations**

1. Open `odyssey_advanced.html` and read the mission instructions.
2. Press **I'm Ready**, then choose a mission objective and accept the briefing.
3. Work through the six phases, making decisions about orbit, vehicle, payload and operations.
4. Review your results in the debrief.

---

## Technology

| Area | Tools |
|------|-------|
| Structure and styling | HTML5, CSS3 (single file per experience) |
| Interactivity | Vanilla JavaScript |
| 3D graphics | Three.js r128 |
| Hand tracking | MediaPipe Hands and Camera Utils |
| Voice | Web Speech API (speech synthesis and recognition) |
| Typography | Google Fonts (Rajdhani, Orbitron, Exo 2) |
| Progress storage | Browser local storage (beginner academy) |

---

## Learning Outcomes

By the end of the experience, learners should be able to:

- Explain how staging, thrust and mass affect a rocket's launch.
- Describe how gravity and velocity determine whether an object enters orbit or falls back.
- Identify the trade-offs between mass, power, budget and science value in spacecraft design.
- Recognise the roles of communication, power and thermal systems in a satellite.

---

## Accessibility and Privacy

- **Single-file design:** no installation, accounts or sign-in are required.
- **Data stays on the device:** the beginner academy stores progress in the browser's local storage. No personal data is sent to a server by our code.
- **Permissions are optional:** microphone and camera access are requested only for voice and gesture features, and the main experience works without them.
- **Clear labelling:** simplified gameplay values are marked as educational, so learners are not misled into treating them as real mission data.

---


## Roadmap

- Add more missions to the advanced simulator (the Mars 2020 Perseverance mission is already listed as "coming soon").
- Add teacher tools, such as a class progress view and printable certificates.
- Add more languages for younger learners.
- Improve offline use by bundling external libraries with the files.
- Add accessibility options such as larger text and keyboard-only navigation.

---

## Images 
<img width="1726" height="872" alt="Screenshot 2026-11-15 161733" src="https://github.com/user-attachments/assets/e2b00cb6-d18e-4a6c-be6f-b6733563d004" />
<img width="1842" height="876" alt="Screenshot 2026-11-15 161554" src="https://github.com/user-attachments/assets/04ebd889-cebb-42ef-a8e8-571f11fcd120" />
<img width="1867" height="822" alt="Screenshot 2026-11-15 161522" src="https://github.com/user-attachments/assets/98088e1a-7ca2-4cb0-9227-997d09c8c943" />






## Acknowledgements

- NASA for the publicly available mission information for Artemis I, PACE and Mars 2020 Perseverance.
- The open-source communities behind Three.js, MediaPipe and the Web Speech API.

---

*Learning space science should be an adventure.* 🌌
