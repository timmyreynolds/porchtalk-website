# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static HTML/CSS website for the band **Porch Talk**, hosted on GitHub Pages at `www.porchtalkband.com`.

## Development

No build system or dependencies. Open `index.html` directly in a browser to preview. The entire site lives in a single self-contained file.

To serve locally with live reload, you can use any static file server (e.g., `python3 -m http.server`).

## Architecture

The site is a single `index.html` with all CSS embedded in `<style>` tags. Five sections:
- **Listen** — YouTube/SoundCloud embeds
- **Shows** — Upcoming and past shows with venue info and links
- **About Us** — Band description and member names (Timmy, Zane, Kevin, John)
- **Merch** — Merchandise grid (currently disabled with "Coming Soon" overlay)
- **Footer** — Social links (Instagram, YouTube, SoundCloud, email)

Mobile breakpoint is at 768px.

## Brand Colors

Defined in `src/Reference.css` (reference only — not linked in index.html):
- `#CD9602` — Middle yellow (primary brand)
- `#DB730B` — Middle orange (buttons)
- `#505F33` — Middle green (backgrounds)
- `#79A1A3` — Middle blue (headers)
- `#FCF7EB` — Off-white (page background)

Assets (images) live in `src/assets/`.
