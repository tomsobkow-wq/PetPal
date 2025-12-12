# PetPal - Apple App Store Support Website

This repository contains the official website for PetPal, designed to support the app's deployment on the Apple App Store.

## Overview

PetPal is a comprehensive pet care management application. This website provides all the necessary pages required by Apple's App Store guidelines, including:

- **Landing Page** (`index.html`) - Main homepage showcasing the app
- **Privacy Policy** (`privacy-policy.html`) - Required by Apple App Store
- **Terms of Service** (`terms-of-service.html`) - User agreement and terms
- **Support Page** (`support.html`) - Help center and contact information

## Apple App Store Requirements

When submitting an app to the Apple App Store, Apple requires:

1. ✅ **Privacy Policy URL** - Available at: `https://[your-domain]/privacy-policy.html`
2. ✅ **Support URL** - Available at: `https://[your-domain]/support.html`
3. ✅ **Terms of Service** (recommended) - Available at: `https://[your-domain]/terms-of-service.html`

## Website Structure

```
PetPal/
├── index.html              # Landing page
├── privacy-policy.html     # Privacy policy (required by Apple)
├── terms-of-service.html   # Terms of service
├── support.html            # Support and contact page (required by Apple)
├── css/
│   └── style.css          # Stylesheet for all pages
├── images/                 # Directory for images (add app screenshots, logo, etc.)
└── README.md              # This file
```

## Deployment via GitHub Pages

### Quick Setup

1. **Enable GitHub Pages:**
   - Go to your repository settings on GitHub
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select the branch you want to deploy (e.g., `main` or `claude/petpal-app-store-website-019eSRKRB2me1yGbXsKXE6LG`)
   - Click "Save"

2. **Your website will be available at:**
   ```
   https://[username].github.io/PetPal/
   ```

3. **Use these URLs in App Store Connect:**
   - Privacy Policy: `https://[username].github.io/PetPal/privacy-policy.html`
   - Support URL: `https://[username].github.io/PetPal/support.html`
   - Marketing URL (optional): `https://[username].github.io/PetPal/`

### Custom Domain (Optional)

To use a custom domain:

1. Add a `CNAME` file to the repository with your domain name
2. Configure DNS settings with your domain provider
3. Enable HTTPS in GitHub Pages settings

## Customization

### Update Contact Information

Before deploying, update the following email addresses in the HTML files:

- `support@petpal.app` → Your support email
- `privacy@petpal.app` → Your privacy contact email
- `legal@petpal.app` → Your legal contact email
- `bugs@petpal.app` → Your bug report email
- `feedback@petpal.app` → Your feedback email
- `hello@petpal.app` → Your general inquiries email

### Add App Store Links

Update the App Store download links in `index.html`:

```html
<!-- Replace # with your actual App Store URL -->
<a href="#" class="cta-button">Download on App Store</a>
```

### Add Images

1. Add your app icon, screenshots, and other images to the `images/` folder
2. Update image references in the HTML files

### Customize Content

Feel free to modify the content to match your specific app features and requirements:

- Update feature descriptions in `index.html`
- Customize privacy policy details in `privacy-policy.html`
- Adjust terms of service in `terms-of-service.html`
- Add more FAQs in `support.html`

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with flexbox and grid
- **Vanilla JavaScript** - Minimal JS for form handling
- **Responsive Design** - Mobile-first approach

## Browser Support

The website is compatible with:

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Development

To test locally:

1. Clone the repository
2. Open `index.html` in a web browser
3. Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js http-server
   npx http-server
   ```
4. Navigate to `http://localhost:8000`

## License

This website template is provided as-is for use with the PetPal app.

## Support

For questions about this website or the PetPal app:

- Email: support@petpal.app
- Repository Issues: [GitHub Issues](https://github.com/tomsobkow-wq/PetPal/issues)

---

**Note:** Remember to update all placeholder content, email addresses, and links before deploying to production and submitting to the App Store.
