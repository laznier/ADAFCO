# ADAFCO Bullseye / Air Battle Trainer

An interactive, browser-based simulator for Air Defense Artillery Fire Control Officers (ADAFCOs).  
This tool allows ADAFCOs and C2 operators to practice bullseye calls, track engagement procedures, and strategic decision-making in a simulated, time-constrained environment.

> **Disclaimer:** This simulator uses unclassified data only. Do **NOT** use any ranges, procedures, or contracts shown here for real mission planning.  
> This software is not endorsed by, nor affiliated with, the U.S. Department of Defense.

---

## 🎯 Features
- **Bullseye Practice Mode** – Timed, scored bullseye location drills.
- **Air Battle Mode** – Full defensive scenario with multiple threat types.
- **REDWOOD / FIREBALL Simulation** – Simulate quadrant-specific and full TBM defense authorizations.
- **Track Engagement Management** – AFFIRM/NEGATE, HOLD FIRE, and engagement hotkeys.
- **Realistic Threats** – Hostile aircraft, TBMs, cruise missiles, and friendly returns.
- **Mobile-Friendly UI** – Works on tablets and phones with touch controls.
- **Scoring & Feedback** – Track performance across levels.
- **Voice Command Support** – Issue commands verbally for immersive training.

---

## 🖥 Controls & Hotkeys
| Action | Key |
|--------|-----|
| AFFIRM COVER | `A` |
| NEGATE COVER | `N` |
| BIRDS AWAY | `W` |
| HOLD FIRE | `H` |
| KILL (manual vanish) | `K` |
| Re-orient Patriot Radar | `O` |
| Pan Map | Arrow Keys |
| Zoom | `+` / `-` |
| Multi-Select | `Shift + Drag` |

Mobile toolbar replicates these commands.

---

## 🎙 Voice Command Instructions
The simulator supports **voice-triggered commands** for faster and more realistic ADAFCO operations.

1. **Enable Microphone Access**
   - On first launch, click the **🎤 Dictate** button at the bottom-left of the screen.
   - Grant microphone permission when prompted by your browser.

2. **Speaking Commands**
   - Use standard ADAFCO phraseology:
   - Hold CRTL and make calls to the TD C/S "GUARDIAN" from the BCC C/S "BIGFOOT"
     - `"Cover Track [ID]"`
     - `"Cover Group Bullseye [bearing/distance]"`
     - `"Engage Track [ID]"` or `"Engage Group Bullseye [bearing/distance]"`
     - `"Hold Fire Track [ID]"`
     - `"SL, ADAFCO, Request Redwood Hot [NW/NE/SW/SE] Quadrant"`
     - `"Crew, Fireball Fireball Fireball"` (global TBM defense)
     - `"reorient [NW/NE/SW/SE] Quadrant" PTL (or Patriot target line) bearing 230"`
     - `"What State"`

3. **Best Practices**
   - Speak clearly and at a steady pace.
   - Use a noise-free environment for best recognition.
   - Commands map directly to hotkey actions (e.g., `"Birds Away"` = press `W`).

4. **Troubleshooting**
   - If no voice is detected, click **🎤 Dictate** again to reset the input.
   - iOS Safari may require the first tap anywhere on the page to enable audio/voice features.

---

