# AxionX Website

Professional landing page and website for AxionX - Day to Day AI implementation and advisory services.

## 🎯 Overview

This website is designed for **£100M+ revenue companies** in the UK, providing:
- Professional landing page with hero section and service overview
- Detailed About Us, Services, and Contact pages
- Newsletter integration with Substack
- Contact form powered by Formspree
- Microsoft Clarity analytics integration
- Responsive design optimised for all devices

## 📁 Project Structure

```
axionx-website/
├── index.html          # Main landing page
├── about.html          # About Us page
├── services.html       # Services detail page
├── contact.html        # Contact form page
├── logo-mockups.html   # Logo variations showcase
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── netlify.toml        # Netlify configuration
├── _redirects          # URL redirects configuration
└── README.md           # This file
```

## 🚀 Deployment to Netlify

### Method 1: GitHub Integration (Recommended)

1. **Push to GitHub:**
   ```bash
   cd axionx-website
   git init
   git add .
   git commit -m "Initial commit - AxionX website"
   git remote add origin https://github.com/Atownend1/axionx-website.git
   git push -u origin main
   ```

2. **Connect to Netlify:**
   - Log in to [Netlify](https://netlify.com) with your Atownend1 account
   - Click "Add new site" → "Import an existing project"
   - Choose GitHub and select your repository
   - Netlify will auto-detect the settings
   - Click "Deploy site"

3. **Configure Custom Domain:**
   - In Netlify dashboard, go to "Domain settings"
   - Click "Add custom domain"
   - Enter `axionx.uk`
   - Follow DNS configuration instructions

### Method 2: Drag & Drop

1. Log in to [Netlify](https://netlify.com)
2. Drag the entire `axionx-website` folder onto the Netlify dashboard
3. Your site will be deployed instantly
4. Configure custom domain in site settings

## ⚙️ Configuration Required

### 1. Formspree Setup

The contact form needs your Formspree form ID:

1. Log in to [Formspree](https://formspree.io) (email: hello@axionx.uk)
2. Create a new form
3. Copy your form ID
4. Update `contact.html` line 102:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
   ```
   Replace `YOUR_FORM_ID` with your actual form ID

### 2. Substack Newsletter

The newsletter links are already configured to point to:
- `https://substack.com/@daytodayai`

If you need to update this, search for "substack.com" in all HTML files.

### 3. Microsoft Clarity

Already configured with your Clarity ID: `twd2w7v9sp`

This is included in all HTML pages and will track:
- User behaviour
- Heatmaps
- Session recordings

## 📧 Email Configuration

Contact form submissions will be sent to: **hello@axionx.uk**

Make sure this email is configured in your Formspree account.

## 🎨 Logo Variations

View all logo mockups by opening `logo-mockups.html` in your browser.

**Recommended usage:**
- **Primary:** Variation 1 (gradient text on white)
- **Hero sections:** Variation 2 (white on gradient)
- **Favicon:** Use the "AX" badge from Variation 4

## 📱 Features

### Landing Page (index.html)
- Hero section with gradient background
- Value proposition highlighting 3 key problems solved
- Services overview with 4 main offerings
- Call-to-action sections
- Newsletter signup
- Professional footer

### About Us (about.html)
- Company mission and vision
- "Why Choose Us" section with 4 key differentiators
- 4-step approach methodology
- Enterprise-focused messaging

### Services (services.html)
- Detailed descriptions of 4 core services:
  - AI Strategy & Advisory
  - AI Implementation & Integration
  - Executive AI Education
  - Custom AI Solutions
- Benefits and key deliverables for each
- Target audience for each service

### Contact (contact.html)
- Professional contact form with Formspree integration
- Company information display
- Estimated revenue field for qualifying leads
- Service interest selection
- Timeline preferences

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables
- **Vanilla JavaScript** - No frameworks for faster loading
- **Formspree** - Form handling
- **Microsoft Clarity** - Analytics
- **Netlify** - Hosting and deployment

## 📊 Analytics & Tracking

### Microsoft Clarity
- Already integrated on all pages
- Dashboard: https://clarity.microsoft.com
- Project ID: `twd2w7v9sp`

### Conversion Tracking
Key conversion points to monitor:
1. "Book a 15-Minute Call" button clicks
2. Contact form submissions
3. Newsletter signups
4. Service page visits

## 🎯 Target Audience

- **Company Size:** £100M+ annual revenue
- **Geography:** United Kingdom
- **Decision Makers:** C-suite, VP-level
- **Industries:** Enterprise organisations across all sectors
- **Pain Points:** 
  - Data quality issues
  - Manual task automation needs
  - AI literacy gaps

## 📝 Content Guidelines

All content follows these principles:
- **UK English spelling** (e.g., "organisation," "optimise")
- **GBP currency** (£)
- **Professional tone** suitable for executive audience
- **Value-focused** messaging (bridge noise to value)
- **No AI hype** - practical implementation focus

## 🔄 Updates & Maintenance

To update content:

1. Edit the relevant HTML file
2. Test locally by opening in a browser
3. Commit and push to GitHub (if using Git integration)
4. Netlify will auto-deploy in ~1 minute

### Quick Content Updates

**Hero Section:** Edit `index.html` lines 58-75
**Services:** Edit `services.html` sections starting at line 37
**Contact Info:** Update `contact.html` lines 85-165

## 🔗 Important Links

- **Live Site:** https://axionx.uk
- **Netlify Dashboard:** https://app.netlify.com (login: Atownend1)
- **Formspree:** https://formspree.io (email: hello@axionx.uk)
- **Microsoft Clarity:** https://clarity.microsoft.com
- **Substack:** https://substack.com/@daytodayai

## 📞 Support

For technical issues or questions:
- Email: hello@axionx.uk
- Review documentation in this README
- Check Netlify deployment logs

## ✅ Pre-Launch Checklist

Before going live, ensure:
- [ ] Formspree form ID updated in contact.html
- [ ] Custom domain (axionx.uk) configured in Netlify
- [ ] SSL certificate active (automatic via Netlify)
- [ ] Test all navigation links
- [ ] Submit test contact form
- [ ] Verify newsletter link opens Substack
- [ ] Test on mobile devices
- [ ] Check Microsoft Clarity is tracking
- [ ] Review all copy for typos
- [ ] Test all CTAs (Call-to-Action buttons)

## 🎨 Customisation

### Colours
Edit CSS variables in `styles.css` (lines 8-19):
```css
:root {
    --primary-purple: #6B46C1;
    --primary-blue: #3B82F6;
    --accent-color: #10B981;
}
```

### Logo
- Current logo uses gradient text effect
- View alternatives in `logo-mockups.html`
- Logo files should be placed in `/images` folder (create if needed)

### Fonts
Currently using system fonts for fast loading. To add custom fonts, include in `<head>` of HTML files.

---

**Built with ❤️ for AxionX - Bridging the gap between AI noise and AI value**
