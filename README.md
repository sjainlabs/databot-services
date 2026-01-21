```markdown
![DataBot Services logo](assets/logo.jpeg)

# DataBot Services

Modern data engineering and analytics solutions.

## Local Development

You can preview the site locally with no build step required because Tailwind is loaded via CDN.

1. Clone the repository:
   ```bash
   git clone https://github.com/sjainlabs/databot-services.git
   cd databot-services
   ```

2. Open the site in your browser:
   - Option A (quick): Open `index.html` directly in your browser.
   - Option B (recommended): Run a simple static server for better routing and CORS:
     - Python 3:
       ```bash
       python3 -m http.server 8000
       # then open http://localhost:8000
       ```
     - Node (using `serve`):
       ```bash
       npx serve .
       # then open the URL printed by serve
       ```

Note: The project uses Tailwind via CDN with a small inline configuration, so you don't need to run Tailwind locally to preview.

## Deploy to GitHub Pages

You can host the site on GitHub Pages with minimal setup.

Option A — Recommended (use `main` branch, root):
1. Push your code to the `main` branch.
2. In the repository settings on GitHub, go to **Pages**.
3. Under **Source**, choose the `main` branch and the root (`/`) folder, then save.
4. GitHub will publish the site at:
   ```
   https://<your-github-username>.github.io/databot-services/
   ```

Option B — Using `gh-pages` branch or GitHub Actions:
- You can push a static build or configure a GitHub Actions workflow to publish to `gh-pages`. See GitHub Pages docs for details:
  https://docs.github.com/en/pages

## Notes

- Brand colors and UI are implemented using Tailwind utility classes with an inline Tailwind configuration for the `databot` color palette.
- If you want to migrate to a full Tailwind build process (for production optimizations like purge/scan), set up a local build with PostCSS and the Tailwind CLI and replace the CDN usage.
```
