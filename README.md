# Roll Call

A lightweight, single-file student attendance register tool, built for the **GUILD SA Buildathon 01 Qualification Challenge** (Eduvos Pretoria pilot).

No backend, no build step, no frameworks — just `index.html`. Open it in a browser and it works.

## Features

- **Add attendees** with a name and student number
- **Check in / check out** attendance with one click, timestamped automatically
- **Duplicate prevention** — student numbers are normalized and checked against existing records
- **Search and filter** attendees by name, student number, or attendance status
- **Live dashboard** — total registered, present, not checked in, and attendance rate (with an animated progress ring)
- **Edit or remove** individual records inline
- **Reset all data** through a custom confirm → loading → success flow (no native browser popups)
- **CSV export** of the full register
- **Light / dark mode** toggle, remembered across visits
- **Data persistence** via `localStorage` — your register survives a page refresh
- Fully responsive, keyboard-accessible, and respects reduced-motion preferences

## Getting started

No installation needed.

1. Download `index.html`
2. Open it in any modern browser (double-click, or drag it into a browser tab)

That's it — there's no server, no `npm install`, no dependencies to fetch.

## Tech stack

Vanilla HTML, CSS, and JavaScript only. No React, Vue, Angular, jQuery, or CSS frameworks. No backend or database — all data is stored client-side in `localStorage`.

## Project structure

```
.
├── index.html      # the entire application (HTML + CSS + JS)
├── Glass_Symbol_polfar.png    # optional, add your own logo image
└── README.md
```

## Live demo

https://joseph17-mancity.github.io/GUILD-SA-Buildathon-01-Qualification-Challenge/

## About this build

Built for GUILD SA's Buildathon 01 qualification challenge: create a browser-based tool for an event organiser to add attendees, record attendance, search records, and monitor statistics — all within a single `index.html` file with no backend.

**AI and tool disclosure:** built with Claude (Anthropic) as an AI-assisted coding tool. No templates or third-party libraries were used; all HTML, CSS, and JavaScript is original.

## License

No license specified. All rights reserved to the author unless stated otherwise.
