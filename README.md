# Space Odyssey: Learn Space Engineering by Doing

**Team:** ODYSSEY
**Demo video:** https://youtu.be/5cPAPZkLiV8

Space Odyssey is a browser-based learning platform in which students design rockets, launch satellites, and plan space missions. Every decision affects the outcome, allowing learners to observe engineering trade-offs in action.

## Problem

Space mission design requires balancing budget, mass, power, communication, and orbital constraints. Students rarely have the opportunity to test these decisions, so the underlying concepts remain abstract.

## Solution

Space Odyssey consists of two modules:

- **Beginner Space Academy** (`odyssey_beginner.html`): five interactive simulations covering rocket launch, orbital mechanics, satellite design, asteroid defence, and planetary rescue, with an integrated "Ask the Scientist" assistant.
- **ODYSSEY Advanced Mission Operations** (`odyssey_advanced.html`): a six-phase mission simulator based on NASA missions (Artemis I, PACE, and Mars 2020 Perseverance), featuring a 3D spacecraft view, live telemetry, and hand-gesture control.

## Screenshots

<img width="1867" height="822" alt="Screenshot 2026-11-15 161522" src="https://github.com/user-attachments/assets/98088e1a-7ca2-4cb0-9227-997d09c8c943" />

<img width="1842" height="876" alt="Screenshot 2026-11-15 161554" src="https://github.com/user-attachments/assets/04ebd889-cebb-42ef-a8e8-571f11fcd120" />

<img width="1616" height="867" alt="Screenshot" src="https://github.com/user-attachments/assets/acdbeac2-f511-4ac2-97ea-45fb74782e59" />

## How to Run

1. Open `odyssey_beginner.html` or `odyssey_advanced.html` in Google Chrome or Microsoft Edge.
2. No installation or account is required. An internet connection is needed on first load.
3. If camera or microphone access fails, start a local server with `python -m http.server 8000` and open `http://localhost:8000`.

## Learning Outcomes

- Rocket staging, thrust, and mass
- Orbital mechanics and gravity
- Spacecraft design trade-offs
- Satellite power, communication, and thermal systems

## Limitations

- The advanced simulator currently supports single-player use only. Team play for up to four participants is planned.
- Physics models are simplified for educational purposes.

## Future Scope

Team play for up to four participants, additional missions, a teacher dashboard, and offline support.
