# 🚀 GitHub Setup Instructions

Follow these steps to deploy the ASG Projects Dashboard to GitHub Pages.

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Create a new repository named: **asg-projects**
3. Make it **Public** (required for GitHub Pages)
4. Do NOT initialize with README (we already have one)
5. Click "Create repository"

## Step 2: Push to GitHub

After creating the repository, GitHub will show you commands. Use these:

```bash
# Add remote
git remote add origin https://github.com/YOUR_USERNAME/asg-projects.git

# Rename branch (if needed)
git branch -M main

# Push to GitHub
git push -u origin main
```

**Replace `YOUR_USERNAME` with your actual GitHub username.**

## Step 3: Enable GitHub Pages

1. Go to your repository: https://github.com/YOUR_USERNAME/asg-projects
2. Click **Settings** (top right)
3. Scroll down to **Pages** section
4. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

GitHub will build your site. Wait 1-2 minutes, then your dashboard will be live at:
```
https://YOUR_USERNAME.github.io/asg-projects/
```

## Step 4: Verify

- Visit your site: `https://YOUR_USERNAME.github.io/asg-projects/`
- Share the link with your team!

## 🔄 Making Updates

To update the dashboard after initial push:

```bash
# Make changes to index.html or README.md

# Stage changes
git add .

# Commit
git commit -m "Update: describe your changes"

# Push to GitHub
git push
```

Changes will deploy automatically within 1-2 minutes.

---

## 📁 Files in This Repository

- **index.html** - Beautiful dashboard UI (main attraction)
- **README.md** - Project documentation
- **SETUP_GITHUB.md** - These instructions
- **.gitignore** - Git ignore patterns

## 🎨 Customization

To customize the dashboard:

1. Edit `index.html` to add your branding
2. Update project metrics in the metrics sections
3. Add or remove project cards as needed
4. Commit and push - GitHub Pages updates automatically

## ❓ Troubleshooting

**GitHub Pages not showing up?**
- Wait 2-3 minutes after enabling Pages
- Check the "Pages" settings to see build status
- Clear your browser cache (Ctrl+Shift+Delete)

**Want to use a custom domain?**
- Go to Settings → Pages → Custom domain
- Add your domain and follow the DNS setup

**Need HTTPS?**
- Automatic! GitHub Pages provides free SSL certificates

---

Ready? Follow the steps above and send the link! 🎉
