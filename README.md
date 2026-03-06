# Resume Website

A professional personal resume website built with HTML and CSS.

This repository contains a responsive single-page website for presenting professional profile information, including experience, projects, skills, certifications, coursework, and education.

## Project Overview

The website is designed as a clean, modern, and mobile-friendly resume experience with:

- Structured sections for profile, experience, projects, skills, and education
- Semantic HTML for clarity and maintainability
- Custom CSS styling with a distinct visual theme
- Responsive layout for desktop and mobile devices
- Subtle motion and reveal effects for improved presentation

## Tech Stack

- HTML5
- CSS3
- Google Fonts (`Space Grotesk`, `Source Serif 4`)

## Repository Structure

- `index.html`: Main resume page and content structure
- `styles.css`: Complete styling, layout, and responsive behavior
- `Hamza's Resume.pdf`: Source resume document used as reference

## Running Locally

No build tools or package installation are required.

1. Clone the repository.
2. Open `index.html` directly in your browser.

For a local development server, you can run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Customization Guide

To update content:

- Edit text and section content in `index.html`
- Update links in the hero and footer sections

To adjust design:

- Modify color variables in `:root` inside `styles.css`
- Tune typography, spacing, and card/panel styles in `styles.css`
- Adjust breakpoints in the media queries for layout behavior

## Deployment

This project can be deployed as a static website on platforms such as:

- GitHub Pages
- Netlify
- Vercel (static hosting)

For GitHub Pages, publish from the `main` branch and set the root as the source.

## License

This repository is intended for personal portfolio and resume use.
