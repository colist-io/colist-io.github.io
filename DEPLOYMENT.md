# GitHub Pages Deployment Guide

This guide will help you deploy the CoList website to GitHub Pages.

## Quick Start

1. **Fork this repository** to your GitHub account
2. **Rename the repository** to `YOUR_USERNAME.github.io` (replace YOUR_USERNAME with your GitHub username)
3. **Enable GitHub Pages** in repository settings
4. **Access your site** at `https://YOUR_USERNAME.github.io`

## Detailed Steps

### Step 1: Fork the Repository

1. Click the "Fork" button in the top-right corner of this repository
2. Select your GitHub account as the destination
3. Wait for the fork to complete

### Step 2: Rename the Repository

1. Go to your forked repository
2. Click "Settings" tab
3. Scroll down to "Repository name" section
4. Change the name to `YOUR_USERNAME.github.io`
5. Click "Rename"

### Step 3: Enable GitHub Pages

1. In your repository, go to "Settings"
2. Scroll down to "Pages" section in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 4: Wait for Deployment

- GitHub will automatically build and deploy your site
- This usually takes 1-2 minutes
- You'll see a green checkmark when deployment is complete

### Step 5: Access Your Site

- Your site will be available at `https://YOUR_USERNAME.github.io`
- GitHub will show you the URL in the Pages settings

## Custom Domain (Optional)

If you want to use a custom domain:

1. Add a `CNAME` file to the root directory with your domain name
2. Configure your DNS settings to point to GitHub Pages
3. Enable "Enforce HTTPS" in Pages settings

## Troubleshooting

### Site Not Loading
- Check that the repository name is exactly `YOUR_USERNAME.github.io`
- Verify GitHub Pages is enabled in Settings > Pages
- Wait a few minutes for deployment to complete

### Images Not Showing
- Ensure image paths are correct (case-sensitive)
- Check that images are committed to the repository
- Verify file extensions match exactly

### Styling Issues
- Clear your browser cache
- Check for any CSS syntax errors
- Ensure all CSS files are properly linked

## Updating Your Site

1. Make changes to your files locally
2. Commit and push changes to the main branch
3. GitHub Pages will automatically rebuild and deploy
4. Changes should be live within 1-2 minutes

## Support

If you encounter issues:
- Check the [GitHub Pages documentation](https://docs.github.com/en/pages)
- Open an issue in this repository
- Contact us at hello@colist.io

---

**Happy deploying! 🚀**

