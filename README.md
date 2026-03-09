# Restaurang Lotus - GitHub Pages Website

A modern, clean restaurant website built with Jekyll and GitHub Pages.

## Quick Start

1. Fork or clone this repository
2. Update `_config.yml` with your GitHub username in the URL
3. Edit the `.md` files to add your actual content (menu, prices, hours, contact info)
4. Push to GitHub
5. Enable GitHub Pages in repository Settings > Pages > Source: main branch

## Files to Customize

| File | What to update |
|------|----------------|
| `_config.yml` | Site title, description, URL |
| `index.md` | Welcome text, opening hours, address |
| `menu.md` | Takeaway menu items and prices |
| `buffet.md` | Buffet prices and included items |
| `hotpot-bbq.md` | Hotpot/BBQ prices and options |
| `contact.md` | Address, phone, email, social links |

## Changing the Theme

The site uses the "minimal" theme by default. To change it, edit `_config.yml`:

```yaml
# Other theme options:
remote_theme: pages-themes/cayman@v0.2.0
remote_theme: pages-themes/slate@v0.2.0
remote_theme: pages-themes/midnight@v0.2.0
```

See all themes: https://pages.github.com/themes/

## Adding Images

1. Create an `assets/images/` folder
2. Add your images there
3. Reference them in markdown: `![Description](assets/images/your-image.jpg)`

## Custom Styling

Create `assets/css/style.scss` with:

```scss
---
---

@import "{{ site.theme }}";

// Your custom styles here
body {
  font-family: 'Your Font', sans-serif;
}
```

## Local Development

```bash
# Install Jekyll
gem install bundler jekyll

# Run locally
bundle exec jekyll serve

# View at http://localhost:4000
```

## License

Free to use for your restaurant website.
