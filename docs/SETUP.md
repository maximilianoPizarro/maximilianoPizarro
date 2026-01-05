# GitHub Pages Setup Guide

This Jekyll site is ready to be deployed to GitHub Pages.

## Quick Start

### 1. Configure GitHub Pages

1. Go to your repository settings on GitHub
2. Navigate to **Pages** section
3. Under **Source**, select:
   - Branch: `main` (or your default branch)
   - Folder: `/docs`
4. Click **Save**

### 2. Local Development (Optional)

To preview the site locally:

```bash
# Install Ruby and Bundler first (if not already installed)

# Install dependencies
cd docs
bundle install

# Run Jekyll server
bundle exec jekyll serve

# Open http://localhost:4000
```

### 3. Deploy

Simply push your changes to the repository:

```bash
git add .
git commit -m "Add Jekyll site for GitHub Pages"
git push origin main
```

GitHub Pages will automatically build and deploy your site within a few minutes.

## Site Structure

```
docs/
├── _config.yml          # Jekyll configuration
├── _layouts/            # HTML layouts
│   └── default.html
├── _includes/           # Reusable components
│   ├── header.html
│   └── footer.html
├── assets/              # Static assets
│   ├── css/
│   │   └── main.css     # Custom styles (Red Hat inspired)
│   └── images/          # Images and icons
├── index.md             # Homepage
├── 404.html             # 404 error page
├── Gemfile              # Ruby dependencies
└── README.md            # Documentation
```

## Customization

### Update Site Information

Edit `_config.yml` to update:
- Site title and description
- Author information
- Social media links
- Navigation menu

### Modify Content

- **Homepage**: Edit `index.md`
- **Styles**: Edit `assets/css/main.css`
- **Layout**: Edit `_layouts/default.html`
- **Header/Footer**: Edit files in `_includes/`

### Add New Articles

Create new markdown files in the `docs/` directory or create a `_posts/` folder for blog posts.

## Features

✅ Responsive design (mobile-friendly)  
✅ Red Hat inspired color scheme  
✅ Modern, clean UI  
✅ SEO optimized  
✅ Fast loading  
✅ Accessible (WCAG compliant)

## Troubleshooting

### Site not updating?

- Wait 5-10 minutes for GitHub Pages to rebuild
- Check repository settings → Pages → Source is set to `/docs`
- Verify `_config.yml` has correct `baseurl` and `url` settings

### Build errors?

- Check GitHub Actions tab for build logs
- Verify all required files are present
- Ensure `Gemfile` is in the `docs/` folder

### Local Jekyll not working?

- Ensure Ruby 2.7+ is installed
- Run `bundle update` to update dependencies
- Check Jekyll version compatibility

## Support

For issues or questions:
- Check [Jekyll documentation](https://jekyllrb.com/docs/)
- Check [GitHub Pages documentation](https://docs.github.com/pages)

