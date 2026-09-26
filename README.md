# 🌌 Frontend Odyssey

20 genuinely useful front-end apps — no frameworks, no build step, just HTML, CSS, and JavaScript. Every project is a single self-contained `.html` file you can open directly in a browser or deploy anywhere in seconds.

Split into **4 levels**, five apps each, increasing in depth — from a password generator to a live weather dashboard pulling real data, to a full analytics dashboard with a synthesized audio-reactive interface.

```
Frontend-Odyssey/
├── Level-1-Novice/          → focused single-purpose tools
├── Level-2-Apprentice/      → localStorage, audio, richer interactivity
├── Level-3-Adept/           → real external APIs, drag & drop, full apps
├── Level-4-Mastermind/      → live dashboards, MediaRecorder, generated audio
└── README.md
```

## 🗺️ The Map

### Level 1 — Novice
| File | What it does |
|---|---|
| `unit-converter.html` | Convert length, weight, and temperature both ways |
| `password-generator.html` | Generate strong random passwords with a live strength meter |
| `bmi-calculator.html` | BMI calculator with metric/imperial toggle and a gauge |
| `tip-splitter.html` | Split a bill with tip percentage and per-person amounts |
| `color-palette-extractor.html` | Drop in any image, extract its dominant color palette |

### Level 2 — Apprentice
| File | What it does |
|---|---|
| `pomodoro-focus-timer.html` | Focus timer with a chime and procedurally generated ambient sound (rain/waves/hum) |
| `markdown-live-editor.html` | Live markdown editor/previewer with export to `.md` or `.html` |
| `expense-tracker.html` | Income/expense tracker with a running balance and 7-day chart |
| `qr-code-generator.html` | Turn any text or URL into a downloadable QR code |
| `habit-tracker-heatmap.html` | GitHub-style contribution heatmap for daily habits |

### Level 3 — Adept
| File | What it does |
|---|---|
| `weather-dashboard.html` | **Live weather** for any city via the free Open-Meteo API (no key needed) |
| `notes-app.html` | Rich-text notes app with search, formatting toolbar, and autosave |
| `currency-converter.html` | **Live exchange rates** via the free Frankfurter API (no key needed) |
| `kanban-task-board.html` | Drag-and-drop task board with priorities and due dates |
| `music-player-visualizer.html` | Local audio player with a real-time frequency visualizer and 3-band EQ |

### Level 4 — Mastermind
| File | What it does |
|---|---|
| `analytics-dashboard.html` | Live-updating analytics dashboard — line chart, donut chart, animated particle backdrop |
| `code-snippet-vault.html` | Searchable, taggable code snippet manager with copy-to-clipboard |
| `resume-builder.html` | Live-preview resume builder — fill a form, print or save as PDF |
| `voice-memo-recorder.html` | Record real voice memos with the MediaRecorder API and a live waveform |
| `smart-planner-calendar.html` | Drag tasks onto a weekly calendar; checking one off plays a synthesized chime |

## 🚀 Running locally

No install, no build tools. Just open any `.html` file in a browser:

```bash
git clone https://github.com/lynxiecreations-crypto/Frontend-Odyssey.git
cd Frontend-Odyssey/Level-1-Novice
open unit-converter.html   # or just double-click it
```

## 🌐 Deploying

Every file is static and self-contained, so any of these work with zero configuration:

- **Netlify** — drag the whole folder onto [app.netlify.com/drop](https://app.netlify.com/drop)
- **Vercel** — `vercel` inside the repo folder
- **GitHub Pages** — see `HOW-TO-PUBLISH.md`

## 📦 Publishing this repo to GitHub

See `HOW-TO-PUBLISH.md` for the exact commands to push this to your repository.

## 🛠️ Built with

Nothing but HTML5, CSS3, and vanilla JavaScript — Canvas API, Web Audio API, MediaRecorder API, `localStorage`, drag-and-drop, and two free no-key public APIs (Open-Meteo for weather, Frankfurter for exchange rates). One CDN script (`qrcode.min.js`) is used for reliable QR encoding. No React, no Vue, no bundlers.

## 📄 License

Free to use, remix, and learn from. Attribution appreciated but not required.

---

*20 useful apps, 4 levels, one folder at a time.*
