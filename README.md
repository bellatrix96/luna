# luna 🌒

**Your cycle intelligence. Architected.**

A personal web app to track your menstrual cycle, mood, energy, and moon phases — and use that data to design your most powerful days.

Built for a full-time employee preparing for GMAT who wants to work *with* her biology, not against it.

## Features

- **4 phase themes** — Rising (purple), Magnetic (terracotta), The Storm (burgundy dark), The Reset (sage) — auto-switches with your cycle
- **Daily log** — 9 energy sliders, mood tags, appetite tracking, journal note
- **Switch On mode** — phase-matched insights in 4 tones (Hype, Coach, Strategic, Playful)
- **Song of the day** — search YouTube and log what you're vibing to
- **Energy dip predictions** with accuracy feedback loop
- **Google Calendar integration** — reads your events and labels them by phase energy
- **GMAT phase intelligence** — shows which sections you're strongest at in each phase
- **Architect suggestions** — adds phase-aware blocks to your calendar
- **Moon phase tracker** synced with your cycle
- **Log history** — every day's entry, searchable
- **Pattern insights** — energy charts and mood clouds from your data

## Setup

See [setup-guide.html](setup-guide.html) for step-by-step instructions to:
1. Host on GitHub Pages (free, ~5 min)
2. Connect Google Calendar (optional)
3. Add YouTube API key for song search (optional)

## Data privacy

All data is stored locally in your browser (`localStorage`). Nothing is sent to any server except Google Calendar and YouTube API calls (which go directly to Google's servers). Your journal notes and cycle data never leave your device.

## Tech

Pure HTML/CSS/JavaScript. No frameworks, no build tools, no dependencies. Just open `index.html`.
