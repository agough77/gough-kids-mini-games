# 📤 GitHub Setup Instructions

## Step 1: Create Repository on GitHub

1. Go to [GitHub.com](https://github.com) and log in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Repository name: `gough-kids-mini-games`
5. Description: "Educational mini games for young children"
6. Choose "Public" (required for free GitHub Pages)
7. **DO NOT** initialize with README, .gitignore, or license (we already have these)
8. Click "Create repository"

## Step 2: Push Your Code to GitHub

GitHub will show you commands. Use these instead (we already initialized):

```bash
git remote add origin https://github.com/YOUR-USERNAME/gough-kids-mini-games.git
git branch -M main
git push -u origin main
```

Replace `YOUR-USERNAME` with your actual GitHub username!

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" (top menu)
3. Scroll down and click "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and folder "/ (root)"
6. Click "Save"

## Step 4: Access Your Game

After a few minutes, your game will be available at:

```
https://YOUR-USERNAME.github.io/gough-kids-mini-games/
```

## 🎉 That's It!

Your game is now:
- ✅ Hosted on GitHub
- ✅ Licensed under MIT (free to use)
- ✅ Playable online via GitHub Pages
- ✅ Available for anyone to clone and modify

## Future Updates

To update your game after making changes:

```bash
git add .
git commit -m "Description of your changes"
git push
```

GitHub Pages will automatically update within a few minutes!

---

**Need help?** Check GitHub's documentation: https://docs.github.com/en/pages
