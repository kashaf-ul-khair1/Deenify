# Deenify — Your Path to Spiritual Growth

> *"And whoever relies upon Allah — then He is sufficient for him."* — Surah At-Talaq 65:3

Deenify is an Islamic companion web app designed to help Muslims stay connected to their Deen in the middle of their busy daily lives. Built as an ICT course project, it brings together essential Islamic tools — prayer times, Quran reader, Hadith, Zakat calculator, Dhikr counter, and Islamic calendar — in one clean, responsive interface.

---

## Pages

| File | Description |
|---|---|
| `index.html` | Home page — hero section, feature overview, app mockup, stats |
| `features.html` | Detailed breakdown of all 6 app features |
| `faq.html` | Frequently asked questions with accordion interaction |
| `about.html` | Team reflections and the story behind Deenify |
| `contact.html` | Contact details and feedback section |
| `css/style.css` | Single external stylesheet shared across all pages |
| `images/logo.jpg` | Deenify brand logo |

---

## Features

- **Prayer Times** — Location-based Salah times with Adhan reminders and Qibla direction
- **Quran Reader** — Full Arabic text, translations, audio recitation, and Tafsir
- **Hadith Collection** — Daily Hadith from Bukhari, Muslim, and other authentic sources
- **Zakat Calculator** — Accurate calculation for all major asset types with live Nisab values
- **Dhikr Counter** — Digital Tasbih with custom phrases, daily goals, and streak tracking
- **Islamic Calendar** — Hijri calendar with key Islamic dates and Ramadan countdowns

---

## Tech Stack

- **HTML5** — Semantic markup across all pages
- **CSS3** — External stylesheet with CSS custom properties, Flexbox, and CSS Grid
- **Vanilla JavaScript** — Lightweight scripts for mobile nav toggle and FAQ accordion
- **Google Fonts** — Cormorant Garamond (display) + Jost (body)
- No frameworks. No dependencies. No build step.

---

## Responsive Design

The layout adapts across three breakpoints:

- **Desktop** (> 900px) — Full multi-column layouts, side-by-side feature details
- **Tablet** (640px – 900px) — Adjusted grid columns, stacked footer
- **Mobile** (< 640px) — Hamburger navigation, single-column layout, condensed spacing

---

## Project Structure

```
deenify/
├── index.html
├── features.html
├── faq.html
├── about.html
├── contact.html
├── css/
│   └── style.css
└── images/
    └── logo.jpg
```

---

## Getting Started

No installation or build process required. Simply open any `.html` file in a browser:

```bash
# Clone or download the project, then open directly
open index.html
```

Or serve it locally with any static server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000` in your browser.

---

## Design System

| Token | Value | Usage |
|---|---|---|
| `--green-deep` | `#0f3020` | Background, navbar, footer |
| `--green-mid` | `#195329` | Primary brand colour |
| `--gold` | `#c9a84c` | Accents, labels, highlights |
| `--cream` | `#faf7f0` | Page background |
| `--font-display` | Cormorant Garamond | Headings and titles |
| `--font-body` | Jost | Body text and UI |

All design tokens are defined as CSS custom properties in `:root` inside `css/style.css`, making it easy to retheme the entire site from one place.

---

## Motivation

We noticed something troubling around us: Muslims were drifting from their practice, not out of lack of faith, but lack of accessible, thoughtful tools. Deenify is our answer — a bridge between Deen and Dunya, built with sincerity and care for the Muslim community.

---

## License

This project was submitted as an ICT course assignment. All content is original work by the team. The Quran verses and Hadith referenced are from the public domain.
*