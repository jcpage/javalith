# javalith

A simple static website hosted on GitHub Pages.

## GitHub Pages Setup

This repository hosts a static website that can be accessed via GitHub Pages. The site includes:

- `index.html` - Main webpage with styling
- `javalith-hero.svg` - Hero image displayed on the site

## Custom Domain Setup

To point your custom domain to this GitHub Pages site:

1. Go to the repository Settings
2. Navigate to the "Pages" section
3. Under "Custom domain", enter your domain name
4. Create a CNAME file in the repository root with your domain
5. Configure your DNS provider to point to GitHub Pages

## Local Development

To view the site locally, simply open `index.html` in your web browser or serve it with a local web server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000` in your browser.