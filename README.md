# Johnny Gravitt — Spa Support Services

Personal portfolio site for pitching spa support services to Asian spas in Astoria, Queens.

## What This Is

A single-page profile site that shows spa owners what I can do for them. Designed to be shown on a phone or sent as a link.

## Services Listed

- Deep Cleaning
- Errands & Supplies
- Staff Massage
- Laundry & Organization
- General Support
- Website Design & Revamp (featured — AI-powered, fast, affordable)

## Features

- **Language toggle** — English, Chinese (中文), Korean (한국) via button in bottom-right corner
- **Tap-to-call** — phone number links directly to (518) 209-7468
- **Mobile responsive** — looks good on phones, tablets, desktop
- **Scroll animations** — sections fade in as you scroll
- **No dependencies** — pure HTML/CSS/JS, no build step

## Files

- `index.html` — the entire site (HTML, CSS, JS all inline)
- `johnny-real.jpg` — profile photo (1024x1024 JPEG)

## How to Use

Open `index.html` in a browser. That's it. No server needed.

To share online, host it anywhere that serves static files (GitHub Pages, Netlify, Vercel, etc.).

## Editing

- **Change phone number**: Search for `5182097468` and replace all instances
- **Change photo**: Replace `johnny-real.jpg` with a new JPEG file (same filename)
- **Edit services**: Find the `services-grid` section in the HTML
- **Edit translations**: Chinese is in `data-zh` attributes on HTML elements. Korean is in the `translations.ko` object in the `<script>` tag at the bottom.
