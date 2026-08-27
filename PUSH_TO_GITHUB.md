# Push Portfolio to GitHub & Go Live

## Step 1: Create the Repo on GitHub

1. Go to https://github.com/new
2. Name: `portfolio`
3. Description: "Justus Okoro - Founder & Full-Stack Engineer"
4. Public ✓
5. **Do NOT initialize with README** (we already have one)
6. Click **Create repository**

## Step 2: Configure Git Locally

Run these commands in your terminal:

```bash
cd portfolio-justus

# Set your git config
git config user.name "Justus Okoro"
git config user.email "your-email@example.com"

# Add all files
git add .

# First commit
git commit -m "Initial commit: Quorum case study and portfolio"

# Add the remote (replace ReignnRule11 with your username)
git remote add origin https://github.com/ReignnRule11/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to https://github.com/ReignnRule11/portfolio/settings
2. Scroll to **Pages** section
3. Source: Select `main` branch
4. Folder: `/root` (or `/` if root doesn't work)
5. Click **Save**

GitHub will build your site. Wait 2-3 minutes.

## Step 4: Your Live Portfolio

Your site will be live at:
```
https://ReignnRule11.github.io/portfolio
```

You can also set a custom domain in GitHub Pages settings if you have one.

## That's It

Every time you update `index.html` and push:
```bash
git add .
git commit -m "Update: Add new case study"
git push
```

Your site updates automatically within 2 minutes.

---

**Next steps after going live:**
- Test the link on mobile and desktop
- Share it in your bio
- Update your Claude Project with "Portfolio live at: [URL]"
- Add the next case study (Sarvam AI chatbot) when ready
