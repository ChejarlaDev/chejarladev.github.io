# Chejarla.in - Personal Website

A minimal, clean personal website hosted on GitHub Pages with custom domain `chejarla.in`.

## Features

- 🎨 Minimal and modern design
- 📱 Responsive layout
- 🔗 Custom domain support (chejarla.in)
- 📄 Privacy policy section for apps
- ⚡ Fast loading with optimized assets

## Setup Instructions

### GitHub Pages Configuration

1. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

2. **Custom Domain Setup:**
   - In the same Pages settings, enter `chejarla.in` in the "Custom domain" field
   - Check "Enforce HTTPS" (recommended)
   - Click "Save"

### DNS Configuration

Configure your DNS provider with the following records:

```
Type: CNAME
Name: @ (or leave empty)
Value: yourusername.github.io
TTL: 3600 (or default)
```

**Note:** Replace `yourusername` with your actual GitHub username.

### Verification

After DNS propagation (can take up to 24 hours), your site should be accessible at:
- https://chejarla.in
- https://www.chejarla.in (if you set up www subdomain)

## File Structure

```
├── index.html              # Main homepage
├── CNAME                   # Custom domain configuration
├── README.md              # This file
└── privacy-policy/        # Privacy policies for apps
    └── index.html         # Sample privacy policy
```

## Customization

### Updating Content

- Edit `index.html` to modify the main page content
- Update `privacy-policy/index.html` for your privacy policy
- Add more pages by creating additional HTML files

### Styling

The site uses inline CSS for simplicity. You can:
- Modify the styles in the `<style>` section of each HTML file
- Add external CSS files for more complex styling
- Include JavaScript for interactive features

## Privacy Policy

The `privacy-policy/` directory is set up to host privacy policies for your applications. You can:

1. Create separate HTML files for different apps
2. Use the existing template as a starting point
3. Customize the content based on your specific needs

## Support

For GitHub Pages issues, refer to the [GitHub Pages documentation](https://docs.github.com/en/pages).

## License

This project is open source and available under the [MIT License](LICENSE). 