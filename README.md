# Wiley University — Spring 2026 Final Exam Schedule

Interactive, single-file web app for the Spring 2026 final examination schedule at Wiley University (Marshall, Texas).

**Live site:** https://wiley-finals-spring-2026.netlify.app

## Features

- **Day-by-day schedule** — Tue Apr 28, Wed Apr 29, Thu Apr 30, plus Fri May 1 make-up day
- **Live search** across course code, title, instructor, or room
- **Filters** by time slot, department, building, and instructor
- **Three views** — Cards, Table, Timeline
- **My Schedule** — pin exams, detect time conflicts, persist via localStorage
- **Shareable schedule** link (URL hash)
- **Exports** — `.ics` calendar or `.csv` (full or just pinned)
- **Countdown** to next exam
- **Building legend** with room-usage indicators
- **Dark mode** (respects system preference)
- **Print-optimized** stylesheet
- **Keyboard shortcuts** — `/` search, `1`–`4` days, `F` filters, `S` my schedule, `B` buildings

## Tech

- Single self-contained `index.html` (~590 KB including base64-embedded Wiley W mark)
- No build step, no external dependencies beyond Google Fonts (Fraunces + Inter)
- Hosted on Netlify with security headers and 5-minute edge cache

## Deploy

Updates deploy via Netlify CLI:

```bash
netlify deploy --prod --dir=. --site=6bdc4ff3-32c3-48ec-a9df-93f269c4edbc
```

## Brand

Wiley University official purple `#4B2E83` and gold `#C5A572`. Varsity W mark embedded from official brand assets.

Go Forth Inspired.
