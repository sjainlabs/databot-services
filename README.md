# DataBot Services

Modern data engineering and analytics solutions website.

## About

DataBot Services is a data engineering and analytics company founded by [Sohil Jain](https://www.linkedin.com/in/jainsohil/).

## Website

This repository contains the static website for DataBot Services, built with:
- HTML5 with semantic structure
- Tailwind CSS (via CDN) with custom brand colors
- Vanilla JavaScript for interactions

### Brand Colors

The website uses a custom color palette defined in the Tailwind configuration:

**DataBot Primary (Blue/Indigo)**
- Used for primary branding, navigation, and CTAs
- Colors: `databot-primary-{50-900}`
- Base: `#667eea` (databot-primary-500)

**DataBot Secondary (Purple)**
- Used for gradients and accent elements
- Colors: `databot-secondary-{50-900}`
- Base: `#a855f7` (databot-secondary-500)

**Founder Accent (Sohil Jain)**
- Personal accent color representing the founder
- Colors: `founder-accent-{light, DEFAULT, dark}`
- Base: `#764ba2` (founder-accent)

## Features

- Responsive design (mobile and desktop)
- Mobile navigation menu
- Smooth scrolling navigation
- Contact form
- Service showcase
- Company information

## Deployment

The site is configured for GitHub Pages deployment. Simply enable GitHub Pages in the repository settings to deploy.

## Local Development

To run locally:
```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080 in your browser.