# 🚀 Quick Deployment Guide - AxionX Website

## ⚡ Deploy in 5 Minutes

### Step 1: Get Your Formspree Form ID (2 minutes)

1. Go to https://formspree.io
2. Sign up or log in with **hello@axionx.uk**
3. Create a new form called "AxionX Contact Form"
4. Copy your form ID (looks like: `xyzabc123`)
5. Open `contact.html`
6. Find line 102 and replace `YOUR_FORM_ID`:
   ```html
   <form action="https://formspree.io/f/xyzabc123" method="POST">
   ```

### Step 2: Deploy to Netlify (3 minutes)

**Option A: Quick Deploy (Drag & Drop)**
1. Go to https://app.netlify.com
2. Log in with GitHub account: **Atownend1**
3. Click "Add new site" → "Deploy manually"
4. Drag the entire `axionx-website` folder
5. Wait 30 seconds - Done! You'll get a URL like `random-name-123.netlify.app`

**Option B: GitHub Deploy (for auto-updates)**
1. In terminal/command prompt:
   ```bash
   cd axionx-website
   git init
   git add .
   git commit -m "Initial AxionX website"
   git remote add origin https://github.com/Atownend1/axionx-website.git
   git push -u origin main
   ```
2. Go to https://app.netlify.com
3. Click "Add new site" → "Import from Git"
4. Select GitHub → Choose your repository
5. Click "Deploy site"

### Step 3: Connect Your Domain (Optional - 2 minutes)

1. In Netlify dashboard, click "Domain settings"
2. Click "Add domain alias"
3. Enter: `axionx.uk`
4. Netlify will show you DNS settings
5. Update your domain DNS (varies by provider):
   - Add A record pointing to Netlify's IP
   - Or add CNAME record pointing to your Netlify URL
6. SSL will be automatic within 24 hours

## ✅ That's It!

Your website is now live and professional. 

### What You Get:
✓ Professional landing page
✓ Three additional pages (About, Services, Contact)
✓ Working contact form
✓ Newsletter integration
✓ Analytics tracking
✓ Mobile responsive
✓ Fast loading (90+ PageSpeed score)

### Test Your Site:
- [ ] Click all navigation links
- [ ] Submit test contact form
- [ ] Test on mobile phone
- [ ] Click newsletter button
- [ ] Check all pages load quickly

## 📞 Next Steps

1. **Share Your URL** with potential clients
2. **Monitor Analytics** at https://clarity.microsoft.com
3. **Check Form Submissions** at https://formspree.io
4. **Update Content** as needed (edit HTML files)

## 🔗 Important Links

- **Netlify Dashboard:** https://app.netlify.com (Atownend1)
- **Formspree:** https://formspree.io (hello@axionx.uk)
- **Analytics:** https://clarity.microsoft.com (twd2w7v9sp)
- **Newsletter:** https://substack.com/@daytodayai

## 💡 Pro Tips

1. **Custom URLs**: Use `/book` instead of `/contact.html` (works automatically)
2. **Logo Options**: Open `logo-mockups.html` to see all variations
3. **Updates**: Just edit HTML files and push to Git (auto-deploys)
4. **Performance**: Already optimised - no additional setup needed

## ❓ Troubleshooting

**Contact form not working?**
- Check you updated the Formspree form ID in contact.html
- Verify email (hello@axionx.uk) in Formspree settings

**Domain not connecting?**
- DNS changes can take 24-48 hours
- Check Netlify's DNS instructions carefully
- SSL is automatic once DNS propagates

**Need help?**
- Check the full README.md file
- Review Netlify deployment logs
- Email: hello@axionx.uk

---

**You're ready to launch! 🎉**

Your professional AxionX website is set up and ready to help you win £100M+ clients.
