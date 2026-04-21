# Sensol Website

Marketing website for [Sensol](https://sensolltd.co.uk) — AI-native research & software for SEND (Special Educational Needs and Disabilities).

## About

Sensol is building the research, platform, and agentic AI to improve outcomes for the 638,745 children with active EHCPs in England. This site communicates the problem, the product, the team, and the research.

## Tech Stack

- **Pure HTML/CSS/JS** — no framework, no build step required
- **Fonts:** EB Garamond (serif) + IBM Plex Mono (monospace) via Google Fonts
- **Animations:** Canvas-based node graph (hero), IntersectionObserver scroll reveals, count-up ticker
- **Responsive:** Mobile breakpoints at 960px

## Project Structure

```
/
├── index.html        # Single-page site — all CSS and JS are inline
├── assets/
│   └── sensol-logo.png   # Logo / favicon
└── README.md
```

## Running Locally

No build step needed. Just open `index.html` in a browser, or serve it with any static file server:

```bash
# Python
python3 -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080`.

## Deploying

This is a static site and can be deployed anywhere:

- **GitHub Pages:** Push to a repo, enable Pages on the `main` branch root
- **Netlify / Vercel:** Drag and drop the folder, or connect the repo
- **Custom server:** Upload `index.html` and `assets/` to your web root

## Sections

| # | Section | ID |
|---|---|---|
| — | Hero | `#top` |
| 01 | The Crisis | `#crisis` |
| 02 | Product | `#product` |
| 03 | Why Sensol | `#whyus` |
| 04 | Team | `#team` |
| 05 | Research & Writing | `#research` |
| 06 | Contact | `#contact` |

## Contact

**info@sensolltd.co.uk** · Sensol Limited · Registered in England & Wales
