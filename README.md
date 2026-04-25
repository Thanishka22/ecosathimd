# EcoSathi MD 🌿

**Environmental Concern Reporter for Maryland Residents**

EcoSathi MD is a single-page civic tool that helps Maryland residents report, analyze, and collectively document environmental concerns — powered by Google Gemini AI.

---

## Screenshots

### Community Feed
![Community Feed](screenshots/community-feed.png)

---

## Features

### AI-Powered Analysis
- Submit an environmental concern with issue type, location, description, time, and any health impacts
- Gemini AI structures the observation and flags it as **ACUTE** (immediate risk) or **CHRONIC** (ongoing)
- Displays relevant reporting agencies with phone numbers for acute concerns:
  - **MDE** — Maryland Dept. of Environment: 1-800-633-6101
  - **EPA Region 3** — Mid-Atlantic Office: 800-438-2474

### Complaint Draft Generation
- One-click AI-generated formal complaint letter ready to submit to authorities
- Copy to clipboard for easy use

### Community Feed
- All reports stored locally and displayed in a community feed
- Residents can:
  - Click **"I've seen this too"** to raise awareness
  - Click **"Add testimony"** to corroborate a report
- Report status updates automatically:
  | Testimonies | Status |
  |-------------|--------|
  | 0–4 | New |
  | 5–24 | Gathering evidence |
  | 25+ | Ready to file |

### Collective Draft
- At **15 testimonies**, a "Generate Collective Draft" button appears
- Gemini summarizes all community observations into a neutral, factual group report
- Copy to clipboard for coordinated submission

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| UI | HTML5 + CSS3 (no frameworks) |
| Logic | Vanilla JavaScript |
| AI | Google Gemini API (`gemini-2.5-flash`) |
| Storage | `localStorage` (no backend) |

---

## How to Run

1. Clone or download this repo
2. Open `index.html` in any browser
3. No server, no install, no dependencies

```bash
git clone https://github.com/Thanishka22/ecosathimd.git
cd ecosathimd
open index.html
```

---

## Project Structure

```
ecosathimd/
├── index.html        # Entire app — single file
├── screenshots/      # App screenshots
└── README.md
```

---

## Disclaimer

EcoSathi MD is for educational and civic awareness purposes only. It does not provide legal advice. All AI-generated content should be independently verified before submission to any authority.

---

*Built for the Claude Hackathon · April 2026*
