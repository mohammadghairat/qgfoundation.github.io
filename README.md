# Qasem Ghairat Foundation Website

Built with Jekyll for GitHub Pages hosting.

## Site Structure

```
qgf-site/
├── _config.yml          # Site settings
├── _layouts/
│   └── default.html     # Main page template
├── _includes/
│   ├── head.html        # HTML <head> tag
│   ├── header.html      # Navigation
│   └── footer.html      # Footer
├── assets/
│   └── css/main.scss    # All styles
├── index.html           # Homepage
├── about/index.html     # About Us
├── programs/index.html  # Programs
├── resources/index.html # Resources
├── support/index.html   # Support Us
├── contact/index.html   # Contact
└── CNAME                # Custom domain (www.qgfoundation.org)
```

## Contact Form Setup

The contact form uses [Formspree](https://formspree.io) (free tier available).
1. Sign up at formspree.io
2. Create a new form
3. Replace `YOUR_FORM_ID` in `contact/index.html` with your actual form ID

## Editing Content

Each page is a plain HTML file. Open the file, find the text you want to change,
edit it, save, and commit to GitHub — the site updates automatically.
