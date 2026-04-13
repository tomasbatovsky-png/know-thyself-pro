# Know Thyself Pro — Human Design Intelligence

A comprehensive Human Design calculator and analysis tool that generates personalized profiles based on birth data, combining ancient wisdom systems with modern data visualization.

## Features

- **Full Human Design calculation** — Type, Strategy, Authority, Profile, Definition
- **Interactive body graph** — visual representation of defined/undefined centers and channels
- **Detailed interpretations** — personalized descriptions for each aspect of the chart
- **Bilingual** — complete EN/SK support
- **Single-file app** — no server, no dependencies, runs in any browser
- **Print-ready reports** — export-friendly formatting
- **Mobile responsive** — works on all screen sizes

## Architecture

```
know-thyself-pro/
├── know-thyself-pro.html     # Main application (625 KB)
├── know-thyself-v2.html      # V2 with additional features
└── README.md
```

Pure HTML/CSS/JavaScript — no frameworks, no build tools, no external APIs.

## How to Run

Open know-thyself-pro.html in any modern browser.

```bash
python -m http.server 8000
# Open http://localhost:8000/know-thyself-pro.html
```

## Tech Stack

- Vanilla JavaScript with embedded astronomical calculations
- CSS Grid/Flexbox for responsive layout
- Canvas API for body graph visualization
- Google Fonts for typography

## Author

**Tomas Batovsky** — Full-stack developer
Exploring the intersection of self-knowledge tools and modern web technology.
