# Aryan Joshi Portfolio

Personal portfolio website for Aryan Joshi, showcasing full-stack development, AI/ML engineering, and Android development work.

## Overview

This is a responsive, single-page static website built with semantic HTML, custom CSS, and vanilla JavaScript. It presents Aryan's skills, selected projects, availability, and contact information in a dark glass-style interface with cyan and purple accents.

## Features

- Responsive desktop and mobile layouts
- Sticky glass navigation with mobile menu
- Animated hero role/typewriter text
- Scroll-reveal section animations
- Interactive skill and project cards
- Project technology and outcome summaries
- Draggable profile chat button with quick prompts
- Reduced-motion support for accessibility
- Direct GitHub, LinkedIn, and email contact links

## Sections

- **Hero:** Introduction, roles, availability, and primary calls to action
- **About:** Background, location, focus areas, and technology tags
- **Skills:** Frontend, backend, AI/ML, Android, and workflow tools
- **Projects:** TaskFlow, MLVision, and AndroNote
- **Contact:** Email and social profiles

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts: Inter and JetBrains Mono

No framework, package manager, build step, or backend is required.

## Run locally

Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/devaryanjoshi-creator/Portfolio.git
cd Portfolio
```

You can also serve the directory with any static HTTP server. For example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```text
Portfolio/
├── index.html
└── README.md
```

The current page keeps its markup, styles, and scripts in `index.html` so it can be deployed as a static site without a build pipeline.

## Content configuration

Update the following areas in `index.html` when adding real project assets or links:

- Project screenshot paths under `screens/`
- Project GitHub and live-demo URLs
- Resume links
- Profile and social links
- Contact email

## Deployment

The site can be deployed to any static hosting provider, including GitHub Pages, Vercel, Netlify, or Cloudflare Pages. The repository does not require a build command.

## License

No license has been added to the repository yet.
