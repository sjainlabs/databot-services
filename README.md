# DataBot Services

Modern data engineering and analytics solutions website.

## About

DataBot Services is a data engineering and analytics company founded by [Sohil Jain](https://www.linkedin.com/in/jainsohil/).

## Website

This repository contains the static website for DataBot Services, built with:
- HTML5 with semantic structure
- Tailwind CSS (via CDN)
- Vanilla JavaScript for interactions

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

To preview the site locally, you have several options:

### Option 1: Open directly in browser
Simply open the `index.html` file directly in your web browser. This works because the site uses Tailwind CSS via CDN and requires no build step.

### Option 2: Use a static server

**Using Python:**
```bash
python3 -m http.server 8000
```
Then visit http://localhost:8000 in your browser.

**Using Node.js:**
```bash
npx serve .
```

**Note:** Tailwind CSS is loaded via CDN, so no build step or npm install is required.

## Deploy to GitHub Pages

### Option A (Recommended - Simple)

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select the `main` branch
4. Select the root directory (`/`)
5. Click **Save**
6. Your site will be available at `https://<owner>.github.io/<repo>/`

### Option B (Advanced - Using GitHub Actions)

For more advanced deployment workflows, you can use GitHub Actions or push to a `gh-pages` branch. See the [GitHub Pages documentation](https://docs.github.com/en/pages) for more details.