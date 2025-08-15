# AggieMate – UC Davis Schedule Tools

![Made for UC Davis](https://img.shields.io/badge/made%20for-UC%20Davis-blue)  
[![License: GPL v3 & MIT](https://img.shields.io/badge/License-GPLv3%20%26%20MIT-red.svg)](LICENSE)

Enhance UC Davis Schedule Builder with two powerful features — export your schedule as a `.ics` calendar file **and** view RateMyProfessors ratings directly in the course list.  
No sign-ins, no tracking, no bloat — just tools built for Aggies, by an Aggie.

---

## Features

### 📅 Schedule Export (.ics)
- Exports all lectures, discussions, labs
- Adds final exam times
- Downloads a `.ics` file you can import into Google Calendar, Apple Calendar, or any other app
- Works entirely offline — no network calls or account needed

### ⭐ RateMyProfessors Integration
- Shows **overall rating**, **difficulty**, **would take again %**, and **# of reviews**
- Color-coded cards: green (4+), orange (3–4), red (<3), gray (no data)
- Smart caching and re-rendering — no double-fetching
- Animated cow + randomized Aggie-style phrases while loading
- Supports dynamic search, infinite scroll, and toggle ON/OFF
- Fully local — no user data, no tracking

---

## How It Works

AggieMate injects functionality directly into UC Davis Schedule Builder:

1. **DOM Detection** – Observes page content and identifies course + instructor data  
2. **Export Button** – Lets you set the start date of the quarter and instantly download your `.ics` file  
3. **Professor Ratings** – Fetches public RMP data via background script and displays in clean, color-coded cards  
4. **UX Polish** – Adds full-screen loading overlays, toggles, and native-feeling UI  

---

## Privacy
AggieMate does not collect, store, or transmit any personal data.  
All processing happens locally in your browser.  
See the [Privacy Policy](PRIVACY.md) for full details.

---

## Licenses

This project contains code licensed under **two licenses**:

### MIT License (Schedule Export Feature)
- Based on the original [Schedule Builder Export](https://github.com/ajkramer/schedule-builder-export) by Alex Kramer (MIT Licensed)  
- Modified and maintained by **Ehsaan Mohammed** — added support for final exams, `.ics` file downloads, and broader calendar compatibility

### GNU GPL v3 License (RMP Ratings Feature)
- Licensed under the **GNU General Public License v3.0**  
- You may use, modify, and redistribute this software — but:
  - Any **derivative works must also be licensed under GPL v3.0**
  - You **must retain copyright**
  - You **must provide attribution** to the original author: **Ehsaan Mohammed**

#### Additional Terms (per GPL Section 7):
- Any modified versions:
  - **Must not use the name "AggieMate"**
  - **Must not imply affiliation with Ehsaan Mohammed**
  - **Must clearly state that they are modified versions**
- Use of the **AggieMate logo**, **cow GIF**, or other branding/visual assets in forks or derivative projects is **not permitted**

See the [LICENSE](LICENSE) file for full terms.  
More info: [https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)

---

## Credits
Created and maintained by **Ehsaan Mohammed**  
Part of the [AggieMate](https://github.com/ehsaanisme) ecosystem to modernize UC Davis academic tools.  
Original inspiration from RateMyProfessors and the quarterly struggle of picking classes at 3 a.m.