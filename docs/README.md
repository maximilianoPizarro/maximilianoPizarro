# GitHub Pages Site

This directory contains the Jekyll site for my GitHub Pages portfolio.

## Local Development

To run the site locally:

1. Install Ruby and Bundler
2. Install dependencies:
   ```bash
   bundle install
   ```
3. Run Jekyll:
   ```bash
   bundle exec jekyll serve
   ```
4. Open http://localhost:4000

## Structure

- `_config.yml` - Jekyll configuration
- `_layouts/` - HTML layouts
- `_includes/` - Reusable components (header, footer)
- `assets/` - CSS, images, and other static assets
- `index.md` - Homepage content

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch.

The site is configured to publish from the `/docs` folder in the repository settings.

