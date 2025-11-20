# GitHub Pages Setup Guide

Your repository is now ready for GitHub Pages! Follow these steps to deploy:

## Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **+** icon in the top right → **New repository**
3. Name your repository (e.g., `card-design-system`)
4. **DO NOT** initialize with README, .gitignore, or license (we already have these)
5. Click **Create repository**

## Step 2: Connect Local Repository to GitHub

Run these commands (replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual values):

```bash
cd "/Users/samimam2/Desktop/Cards - AI Consolidation"

# Add remote repository
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - **Branch**: `main`
   - **Folder**: `/ (root)`
5. Click **Save**

## Step 4: Access Your Site

After a few minutes, your site will be available at:
```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

## Files Included for GitHub Pages

✅ **index.html** - Landing page with links to demo and showcase  
✅ **demo.html** - Interactive demo with filtering  
✅ **showcase.html** - All cards in a grid view  
✅ **.nojekyll** - Disables Jekyll processing (required for GitHub Pages)  
✅ **style.css** - All card styles  
✅ **README.md** - Project documentation  

## Updating Your Site

After making changes:

```bash
cd "/Users/samimam2/Desktop/Cards - AI Consolidation"

# Stage changes
git add .

# Commit changes
git commit -m "Your commit message"

# Push to GitHub
git push origin main
```

GitHub Pages will automatically rebuild your site within a few minutes.

## Troubleshooting

**Site not loading?**
- Wait 1-2 minutes after enabling Pages
- Check that `index.html` is in the root directory
- Verify `.nojekyll` file exists
- Check repository Settings → Pages for any errors

**Styles not loading?**
- Ensure all file paths are relative (not absolute)
- Check browser console for 404 errors
- Verify `style.css` is in the same directory as HTML files

## Quick Commands Reference

```bash
# Check status
git status

# View commit history
git log --oneline

# View remote URL
git remote -v

# Pull latest changes (if working from multiple locations)
git pull origin main
```

---

**Your repository is ready!** Just connect it to GitHub and enable Pages. 🚀

