# 🚀 Deploy AxionX Website Using Cursor

## Super Easy Deployment with Cursor's Git Integration

Your repository is already initialized and committed locally. Now let's push it to GitHub using Cursor's visual interface!

---

## 📦 Step 1: Open Project in Cursor

1. Open **Cursor**
2. **File** → **Open Folder**
3. Navigate to and select: `axionx-website` folder
4. The folder will open in Cursor

---

## 🔗 Step 2: Create GitHub Repository

Before pushing, create the repository on GitHub:

1. Go to: **https://github.com/Atownend1**
2. Click the **"+" icon** (top right) → **"New repository"**
3. Settings:
   - **Repository name:** `axionx-website`
   - **Description:** "Professional website for AxionX - Day to Day AI"
   - **Visibility:** Private (recommended)
   - ❌ **DO NOT** initialize with README, .gitignore, or license
4. Click **"Create repository"**
5. **Copy the repository URL** (should be: `https://github.com/Atownend1/axionx-website.git`)

---

## 🎯 Step 3: Push to GitHub Using Cursor

### Method A: Using Cursor's Source Control Panel (Easiest)

1. **Open Source Control Panel:**
   - Click the **Source Control icon** in left sidebar (looks like a branch/fork icon)
   - Or press: **Ctrl+Shift+G** (Windows/Linux) or **Cmd+Shift+G** (Mac)

2. **You should see:**
   - ✓ 2 commits already made
   - ✓ Branch: main
   - Message: "No changes to commit"

3. **Publish to GitHub:**
   - Look for the **"Publish Branch"** button at the top
   - OR click the **"..."** menu → **"Remote"** → **"Add Remote"**
   
4. **Add Remote:**
   - If prompted, paste: `https://github.com/Atownend1/axionx-website.git`
   - Name it: `origin`

5. **Push:**
   - Click **"Publish Branch"** or **"Push"** button
   - If prompted, select **"origin"** and **"main"** branch
   - Authenticate with GitHub when prompted

### Method B: Using Cursor's Terminal (Alternative)

1. **Open Terminal in Cursor:**
   - **Terminal** → **New Terminal**
   - Or press: **Ctrl+`** (Windows/Linux) or **Cmd+`** (Mac)

2. **Run these commands:**
   ```bash
   # Add GitHub remote
   git remote add origin https://github.com/Atownend1/axionx-website.git
   
   # Push to GitHub
   git push -u origin main
   ```

3. **Authenticate when prompted**

---

## ✅ Step 4: Verify on GitHub

1. Go to: **https://github.com/Atownend1/axionx-website**
2. You should see all your files!
3. Check the commits are there

---

## 🌐 Step 5: Deploy to Netlify (1 Minute)

### Connect to Netlify

1. Go to: **https://app.netlify.com**
2. Log in with GitHub (Atownend1)
3. Click **"Add new site"** → **"Import an existing project"**
4. Choose **"GitHub"**
5. Find and select: **"axionx-website"**
6. Deploy settings (auto-detected):
   - **Branch:** main
   - **Build command:** (leave empty)
   - **Publish directory:** .
7. Click **"Deploy site"**

**You're live!** You'll get a URL like: `random-name-123.netlify.app`

---

## 🔄 Making Updates with Cursor (Super Easy)

After your site is live, to make changes:

### 1. Edit Your Files in Cursor
- Make changes to HTML, CSS, or any file
- Save the file (Ctrl+S / Cmd+S)

### 2. Commit Changes
- Go to **Source Control panel** (Ctrl+Shift+G / Cmd+Shift+G)
- You'll see changed files listed
- Enter a commit message: "Updated hero section" (or whatever you changed)
- Click the **✓ Commit** button

### 3. Push to GitHub
- Click the **"Sync Changes"** button (↻ icon)
- Or click **"..."** → **"Push"**

### 4. Auto-Deploy
- Netlify detects the GitHub push
- Automatically deploys in ~1 minute
- Your site updates automatically!

---

## 💡 Cursor Pro Tips

### Git Status in Cursor
- **Blue bar** on left of file = Modified
- **Green "U"** = Untracked (new file)
- **Red "D"** = Deleted
- **"M"** = Modified

### Quick Commands
- **Ctrl/Cmd + Shift + G** → Source Control
- **Ctrl/Cmd + `** → Terminal
- **Ctrl/Cmd + P** → Quick file search
- **Ctrl/Cmd + Shift + P** → Command palette

### AI Features in Cursor
- **Ctrl/Cmd + K** → AI edit
- **Ctrl/Cmd + L** → AI chat
- Use AI to help edit your content!

---

## 🎨 Editing Tips for Cursor

### Update Hero Section:
1. Open `index.html` in Cursor
2. Find lines 58-75 (hero content)
3. Edit text
4. Save → Commit → Push → Auto-deploy!

### Change Colors:
1. Open `styles.css`
2. Find lines 8-19 (CSS variables)
3. Change color values
4. Save → Commit → Push → Auto-deploy!

### AI-Assisted Editing:
1. Select text you want to change
2. Press **Ctrl/Cmd + K**
3. Tell Cursor AI what to do: "Make this more professional"
4. Accept changes

---

## 📋 What's Already Done

✅ Git repository initialized
✅ 2 commits made:
  - Initial website commit
  - Added deployment scripts
✅ Branch: `main`
✅ Formspree configured (mldodjpe)
✅ All files ready to push

---

## 🎯 Your Workflow Going Forward

```
Edit in Cursor → Save → Commit → Push → Auto-Deploy
              ↓
    (Changes live in 1 minute!)
```

---

## 🔗 Quick Links

After setup, bookmark these:
- **GitHub Repo:** https://github.com/Atownend1/axionx-website
- **Netlify Dashboard:** https://app.netlify.com
- **Live Site:** (will be assigned by Netlify)
- **Formspree:** https://formspree.io
- **Analytics:** https://clarity.microsoft.com

---

## ❓ Troubleshooting in Cursor

### Can't see Source Control?
- Make sure folder is open in Cursor (not just files)
- Click Source Control icon in left sidebar
- Or press Ctrl/Cmd + Shift + G

### Authentication Issues?
- Cursor will prompt for GitHub login
- You can also set up SSH keys for easier access
- Or use GitHub CLI: `gh auth login`

### Terminal not working?
- Use Cursor's built-in terminal: Terminal → New Terminal
- Make sure you're in the right directory (axionx-website)

### Want to undo a commit?
- Source Control panel → "..." menu → "Undo Last Commit"
- Your changes stay, just uncommits them

---

## 🚀 Ready to Launch!

With Cursor, deployment is visual and easy:

1. **Create GitHub repo** (2 minutes)
2. **Click "Publish Branch"** in Cursor (30 seconds)
3. **Connect to Netlify** (1 minute)
4. **You're live!** ✨

All your code is ready. Just follow the steps above!

---

**Pro Tip:** Once set up, future updates are literally:
1. Edit file in Cursor
2. Save
3. Click "Sync Changes" button
4. Live in 60 seconds!

This is as easy as it gets. Let's launch! 🎉
