# Earnest Documentation Hub

Central repository for all company documentation, accessible via GitHub Pages.

## 🚀 Quick Start

### Viewing Documentation
Visit: `https://[your-org].github.io/docs/`

### Local Development
```bash
# Install dependencies
bundle install

# Run locally
bundle exec jekyll serve

# View at http://localhost:4000
```

## 📁 Structure

```
docs/
├── _company/        # Company docs (mission, values, strategy)
├── _engineering/    # Technical docs (architecture, APIs, standards)
├── _operations/     # IT & ops docs (VPN, security, tools)
├── _people/         # HR docs (benefits, policies, handbook)
├── assets/          # CSS, images, and other assets
├── _layouts/        # Page templates
└── index.md         # Homepage
```

## ✍️ Adding Documentation

1. **Choose the right folder:**
   - `_company/` - Company-wide information
   - `_engineering/` - Technical documentation
   - `_operations/` - IT and operational guides
   - `_people/` - HR and culture documentation

2. **Create a markdown file:**
```yaml
---
layout: default
title: Your Page Title
collection: [company|engineering|operations|people]
order: 1
---

# Your Content Here

Write in markdown...
```

3. **Commit and push** - Changes auto-deploy to GitHub Pages

## 🎨 Markdown Features

- **Headers:** `# H1`, `## H2`, `### H3`
- **Bold:** `**text**`
- **Links:** `[text](url)`
- **Code:** `` `inline` `` or ``` blocks ```
- **Lists:** `- item` or `1. item`
- **Tables:** Supported with pipes `|`

## 🔧 Configuration

- `_config.yml` - Main Jekyll configuration
- `assets/css/style.css` - Custom styling
- `_layouts/default.html` - Page template

## 🚢 Deployment

GitHub Pages automatically deploys from the `main` branch. The workflow:
1. Push to `main`
2. GitHub Actions builds the site
3. Deploys to GitHub Pages
4. Available at your GitHub Pages URL

## 📝 Best Practices

- Keep documentation up-to-date
- Use clear, descriptive titles
- Include examples where helpful
- Review changes before merging
- Add images to `assets/images/`

## 🤝 Contributing

1. Create a feature branch
2. Make your changes
3. Test locally with `bundle exec jekyll serve`
4. Submit a pull request
5. Get review from relevant team

## 💡 Tips

- Use the `order` front matter to control page ordering
- Add descriptions to help with navigation
- Keep sensitive information out of public repos
- Use relative links for internal navigation
