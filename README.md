# Shiven Mishra Portfolio

A command-center style personal portfolio website built with static HTML and Tailwind CSS (CDN).

## Overview

This project showcases:
- Professional summary and contact links
- Skills and tech stack
- Work experience and education timeline
- Project repositories and live links
- Verified certifications

The UI follows a dark, terminal-inspired visual language with amber highlights, custom typography, and responsive layouts.

## Live Project

GitHub repository:
- https://github.com/smishra0606/shiven-mishra-portfolio

## Pages

- `index.html`: Main command-center landing page with anchor-based sections.
- `experience.html`: Full timeline for work experience and education.
- `projects.html`: Extended project repository showcase.
- `skills.html`: Complete skill matrix and technology breakdown.
- `certifications.html`: Certification archive with verification links.

## Tech Stack

- HTML5
- Tailwind CSS via CDN (`https://cdn.tailwindcss.com`)
- Google Fonts (Montserrat, Space Mono)
- Material Symbols Icons
- Static assets (images) served from `assets/`

## Folder Structure

```text
Portfolio/
|-- index.html
|-- experience.html
|-- projects.html
|-- skills.html
|-- certifications.html
|-- assets/
`-- README.md
```

## How to Run Locally

Because this is a static site, no build step is required.

### Option 1: Open Directly

1. Open `index.html` in your browser.

### Option 2: Use a Local Server (Recommended)

Using Python:

```bash
python -m http.server 5500
```

Then open:
- `http://localhost:5500`

Using VS Code Live Server extension is also a good option.

## Customization Guide

- Update personal info and social links in the navigation/sidebar blocks across pages.
- Replace images in `assets/` and update image paths in HTML.
- Modify theme colors in each page's Tailwind config section and CSS variables (`--accent`, `--command-bg`, etc.).
- Add or remove cards in Skills, Projects, Experience, and Certifications sections.

## Deployment

You can deploy this project easily on:
- GitHub Pages
- Netlify
- Vercel

For GitHub Pages (root deployment):
1. Push changes to the default branch.
2. In repository settings, enable Pages.
3. Select source: Deploy from branch (root).

## Author

Shiven Mishra
- GitHub: https://github.com/smishra0606
- LinkedIn: https://linkedin.com/in/smishra0606
