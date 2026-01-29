# Instant Feed Marketing Website

This is the marketing landing page for the Instant Feed platform, which connects local merchants with customers through two mobile apps:

- **MYSHOP** - Merchant app for building online stores, managing menus, accepting orders, and chatting with customers
- **MYFEED** - Consumer app for discovering stores, placing orders, and connecting with local merchants

## Features

- Responsive design that works on all devices
- Separate sections for merchants and consumers
- Clear value propositions and feature highlights
- Modern, professional design with smooth animations
- Ready for GitHub Pages deployment

## Deployment to GitHub Pages

### Option 1: Create a New Repository (Recommended)

1. Create a new repository on GitHub (e.g., `instantfeed-landing` or `yourname.github.io`)
2. Clone this website folder or push it to the new repository:
   ```bash
   cd website
   git init
   git add .
   git commit -m "Initial commit - Instant Feed landing page"
   git branch -M main
   git remote add origin https://github.com/yourusername/repository-name.git
   git push -u origin main
   ```

3. Go to repository Settings → Pages
4. Under "Source", select the `main` branch and root folder
5. Click "Save"
6. Your site will be available at `https://yourusername.github.io/repository-name/`

### Option 2: Use a Custom Domain

1. Follow the steps above to deploy to GitHub Pages
2. In your repository Settings → Pages, add your custom domain
3. Update your DNS settings with your domain provider:
   - Add a CNAME record pointing to `yourusername.github.io`
   - Or add A records pointing to GitHub's IP addresses

### Option 3: Project Page in Existing Repository

1. Push this website folder to a branch in your existing repository
2. In Settings → Pages, select that branch
3. Site will be available at `https://yourusername.github.io/repository-name/`

## File Structure

```
website/
├── index.html      # Main HTML file
├── style.css       # Styles and responsive design
├── script.js       # Interactive features and animations
└── README.md       # This file
```

## Customization

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #2563eb;
    --merchant-accent: #8b5cf6;
    --consumer-accent: #06b6d4;
    /* ... more colors */
}
```

### Content
Edit the text content directly in `index.html` to match your branding and messaging.

### Download Links
Update the "Download" button links in the CTA section when your apps are published to app stores.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## License

Proprietary - All rights reserved
