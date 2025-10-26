# 🚀 GitHub Push Instructions - AxionX Website

## ✅ What's Already Done

✓ Git repository initialized
✓ All files added
✓ Initial commit created
✓ Branch renamed to 'main'
✓ Formspree form ID updated (mldodjpe)

---

## 📋 Next Steps - Push to GitHub

### Option 1: Create New Repository on GitHub (Recommended)

**Step 1: Create Repository**
1. Go to https://github.com/Atownend1
2. Click the "+" icon (top right) → "New repository"
3. Repository name: `axionx-website`
4. Description: "Professional website for AxionX - Day to Day AI"
5. Keep it **Private** (you can make public later)
6. **DO NOT** initialize with README, .gitignore, or license
7. Click "Create repository"

**Step 2: Push Your Code**

Open Terminal/Command Prompt in the `axionx-website` folder and run:

```bash
# Add the GitHub repository as remote
git remote add origin https://github.com/Atownend1/axionx-website.git

# Push your code
git push -u origin main
```

You'll be prompted to log in to GitHub. Use your credentials.

---

### Option 2: Push to Existing Repository

If you already have a repository:

```bash
# Add your repository as remote
git remote add origin https://github.com/Atownend1/YOUR-REPO-NAME.git

# Push your code
git push -u origin main
```

---

## 🔗 Connect to Netlify After GitHub Push

### Automatic Deployment Setup

1. Go to https://app.netlify.com
2. Log in with your GitHub account (Atownend1)
3. Click "Add new site" → "Import an existing project"
4. Choose "GitHub"
5. Authorize Netlify to access your repositories
6. Select `axionx-website` repository
7. Build settings (should auto-detect):
   - **Branch to deploy:** main
   - **Build command:** (leave empty)
   - **Publish directory:** .
8. Click "Deploy site"

**That's it!** Netlify will:
- Deploy your site immediately
- Give you a URL like `random-name-123.netlify.app`
- Auto-deploy on every GitHub push
- Provide free SSL certificate

---

## 🌐 Add Custom Domain (axionx.uk)

Once deployed on Netlify:

1. In Netlify dashboard, go to **"Domain settings"**
2. Click **"Add domain alias"**
3. Enter: `axionx.uk`
4. Netlify will provide DNS settings

### Update Your Domain DNS

Add these records with your domain registrar:

**Option A: Using Netlify DNS (Recommended)**
- Change nameservers to Netlify's (they'll provide these)

**Option B: Using A Record**
```
Type: A
Name: @
Value: 75.2.60.5 (Netlify's load balancer IP)
```

**Also add for www:**
```
Type: CNAME
Name: www
Value: your-site-name.netlify.app
```

SSL certificate will be automatic once DNS propagates (24-48 hours).

---

## 🔄 Making Updates After Initial Push

After your site is live, to make changes:

```bash
# 1. Edit your files (HTML, CSS, etc.)

# 2. Stage changes
git add .

# 3. Commit with a message
git commit -m "Update: description of what you changed"

# 4. Push to GitHub
git push

# Netlify will auto-deploy in ~1 minute!
```

---

## 📊 Verify Everything Works

After deployment, check:
- [ ] Visit your Netlify URL
- [ ] Test all navigation links
- [ ] Submit a test contact form
- [ ] Check form submission arrives at hello@axionx.uk
- [ ] Click newsletter link → should go to Substack
- [ ] Test on mobile device
- [ ] Check Microsoft Clarity is tracking (clarity.microsoft.com)

---

## 🎯 Your URLs After Setup

- **GitHub Repo:** https://github.com/Atownend1/axionx-website
- **Netlify Dashboard:** https://app.netlify.com/teams/Atownend1/sites
- **Live Site (temp):** random-name-123.netlify.app (Netlify assigns this)
- **Live Site (custom):** https://axionx.uk (after DNS setup)

---

## 💡 Pro Tips

### Custom Netlify URL
Before adding your domain, you can customize the random Netlify URL:
1. Site settings → "Change site name"
2. Choose something like: `axionx` or `axionx-ai`
3. Your URL becomes: `axionx.netlify.app`

### Branch Deployments
Netlify can deploy other branches for testing:
- Create a `dev` branch for testing
- Each branch gets its own URL
- Only `main` branch goes to production

### Environment Variables
If you need to add secrets later:
- Netlify dashboard → Site settings → Environment variables
- Add without exposing them in GitHub

---

## ❓ Troubleshooting

**"Authentication failed" when pushing to GitHub**
- Use Personal Access Token instead of password
- GitHub Settings → Developer settings → Personal access tokens
- Generate new token with `repo` permissions
- Use token as password when prompted

**"Repository not found"**
- Make sure you created the repo on GitHub first
- Check the repository name matches exactly
- Verify you're logged into correct GitHub account

**Netlify not auto-deploying**
- Check Netlify has GitHub integration permission
- Verify "Build hooks" are enabled in Netlify settings
- Check deploy notifications in Netlify dashboard

**DNS not updating**
- DNS changes take 24-48 hours
- Use https://www.whatsmydns.net to check propagation
- Make sure you saved DNS changes with registrar

---

## 🎉 You're All Set!

Your AxionX website is now:
✓ Version controlled with Git
✓ Backed up on GitHub
✓ Ready to deploy to Netlify
✓ Set up for automatic deployments
✓ Professional and enterprise-ready

**Next:** Run the commands above to push to GitHub and connect to Netlify!

---

Need help? Check README.md for full documentation.
