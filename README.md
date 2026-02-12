# AG Graphics Production Website

🌐 **Live Site:** https://lekedada.github.io/AG-Graphics-Production/

## 📋 About This Repository

This is the official website for AG Graphics Production, a custom apparel and screen printing business based in Houston, TX.

## ✅ What's Been Set Up

### 1. **CNAME File Created**
- A CNAME file has been added with the suggested domain: `www.aggraphics.com`
- This is a placeholder domain for demonstration purposes

### 2. **GitHub Pages Configuration**
- ✅ GitHub Pages is configured and deployed via Jekyll workflow
- ✅ Site is live at: https://lekedada.github.io/AG-Graphics-Production/
- ✅ Automatic deployments on push to `main` branch

### 3. **Website Files**
- ✅ Multiple HTML pages (Home, Services, Portfolio, Pricing, Design Lab, Contact)
- ✅ Professional CSS styling with light/dark theme support
- ✅ Interactive JavaScript for theme toggling
- ✅ Responsive design for mobile and desktop
- ✅ Logo and image assets

## 🌍 Setting Up Your Custom Domain

**IMPORTANT:** To use a custom domain, you need to:

1. **Purchase or register a domain** from a domain registrar
2. **Configure DNS settings** to point to GitHub Pages
3. **Update the CNAME file** with your actual domain (if different from www.aggraphics.com)

📖 **For detailed instructions, see:** [DOMAIN-SETUP.md](./DOMAIN-SETUP.md)

## 🚀 Quick Start Guide

### Your Site is Already Live!
Visit: https://lekedada.github.io/AG-Graphics-Production/

### To Use a Custom Domain:

1. **Get a domain** (see DOMAIN-SETUP.md for options)
2. **Configure DNS** with your registrar:
   - Add A records pointing to GitHub Pages IPs
   - Add CNAME record for www subdomain
3. **Update CNAME file** (if needed):
   ```bash
   # Edit the CNAME file with your domain
   echo "yourdomain.com" > CNAME
   git add CNAME
   git commit -m "Update domain"
   git push
   ```
4. **Enable HTTPS** in GitHub Settings → Pages

## 📁 Repository Structure

```
AG-Graphics-Production/
├── index.html              # Home page
├── services.html           # Services page
├── portfolio.html          # Portfolio showcase
├── pricing.html            # Pricing information
├── design-lab.html         # Design preview tool
├── contact.html            # Contact form
├── CNAME                   # Custom domain configuration
├── DOMAIN-SETUP.md         # Detailed domain setup guide
├── README.md               # This file
├── styles/
│   └── main.css           # Main stylesheet
├── scripts/
│   └── app.js             # JavaScript functionality
├── assets/
│   ├── AGlogo.jpg         # Company logo
│   └── *.png              # Portfolio images
└── .github/
    └── workflows/
        └── jekyll-gh-pages.yml  # Auto-deployment workflow
```

## 🎨 Features

- **Responsive Design**: Works on all devices (mobile, tablet, desktop)
- **Dark/Light Theme**: Toggle between themes with a button
- **Multiple Pages**: Home, Services, Portfolio, Pricing, Design Lab, Contact
- **Professional Styling**: Modern, clean design
- **Portfolio Gallery**: Showcase your work
- **Contact Form**: Ready for integration with Formspree or custom backend
- **Design Lab**: Upload and preview artwork

## 🔧 Customization

### Update Contact Information
Edit the footer in each HTML file:
```html
<footer>AGgraphicsproduction@gmail.com • 832-289-5771</footer>
```

### Change Colors/Styling
Edit `styles/main.css` to customize:
- Colors (`:root` variables)
- Fonts
- Layout
- Spacing

### Add/Remove Pages
1. Create new HTML file
2. Follow the structure of existing pages
3. Link from navigation in `index.html`

## 📞 Contact Information

- **Email:** AGgraphicsproduction@gmail.com
- **Phone:** 832-289-5771
- **Address:** 6230 Wilcrest Dr, Houston, TX 77072

## 📝 To-Do

- [ ] Purchase custom domain
- [ ] Configure DNS settings
- [ ] Update CNAME file with actual domain
- [ ] Set up Formspree for contact form
- [ ] Add more portfolio items
- [ ] Connect social media accounts

## 🤝 Support

For questions about:
- **Domain setup**: See [DOMAIN-SETUP.md](./DOMAIN-SETUP.md)
- **GitHub Pages**: https://docs.github.com/en/pages
- **Website customization**: Contact repository maintainer

---

**Website Status:** ✅ Live and functional at https://lekedada.github.io/AG-Graphics-Production/

**Custom Domain:** 🟡 Pending (requires domain purchase and DNS configuration)
