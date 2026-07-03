# GitHub Pages Setup Instructions

## How to Enable GitHub Pages

Since the GitHub Actions deployment encountered an error, please enable GitHub Pages manually:

1. **Go to Repository Settings:**
   https://github.com/andreay321/Dashboard/settings/pages

2. **Configure GitHub Pages:**
   - Under "Build and deployment"
   - **Source:** Select "Deploy from a branch"
   - **Branch:** Select "main"
   - **Folder:** Select "/ (root)"
   - Click "Save"

3. **Wait for Deployment:**
   - GitHub will automatically build and deploy your site
   - This takes 1-2 minutes
   - You'll see a green checkmark when ready

4. **Access Your Dashboard:**
   https://andreay321.github.io/Dashboard/

## Alternative: Fix GitHub Actions (if preferred)

If you want to use GitHub Actions instead:

1. Go to: https://github.com/andreay321/Dashboard/settings/pages
2. Under "Build and deployment"
3. **Source:** Select "GitHub Actions"
4. Go to: https://github.com/andreay321/Dashboard/settings/actions
5. Under "Actions permissions", select "Allow all actions and reusable workflows"
6. Save and trigger a new deployment

## Troubleshooting

**If the page shows 404:**
- Wait 2-3 minutes after enabling Pages
- Check that index.html exists in the main branch
- Clear your browser cache

**If deployment fails:**
- Make sure the repository is public (Pages doesn't work on private repos with free GitHub)
- Check that GitHub Pages is enabled for your account

## Current Repository Status

- ✅ Files pushed to GitHub: index.html, README.md
- ✅ Main branch exists
- ⏳ Waiting for GitHub Pages to be enabled manually

Once you complete step 2 above, your dashboard will be live at:
**https://andreay321.github.io/Dashboard/**
