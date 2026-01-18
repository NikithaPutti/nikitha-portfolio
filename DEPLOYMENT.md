# Deployment Guide

This guide will help you deploy your portfolio website to GitHub Pages and Vercel.

## Prerequisites

- GitHub account
- Vercel account (free tier available)
- Git installed on your local machine

## Step 1: Initialize Git Repository

```bash
cd /Users/nikithaputti/Downloads/ProjectInternship
git init
git add .
git commit -m "Initial commit: Portfolio website"
```

## Step 2: Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `portfolio` or `nikitha-portfolio`
3. **Do NOT** initialize with README, .gitignore, or license
4. Copy the repository URL

## Step 3: Push to GitHub

```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git branch -M main
git push -u origin main
```

## Step 4: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings**
3. Scroll down to **Pages** section
4. Under **Source**, select **GitHub Actions**
5. The GitHub Actions workflow will automatically deploy your site

**Note**: The first deployment may take a few minutes. You can check the status in the **Actions** tab.

Your site will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Step 5: Deploy to Vercel

### Option A: Via Vercel Dashboard

1. Go to [Vercel](https://vercel.com) and sign in with GitHub
2. Click **Add New Project**
3. Import your GitHub repository
4. Vercel will auto-detect the configuration
5. Click **Deploy**

### Option B: Via Vercel CLI

```bash
npm i -g vercel
vercel login
vercel
```

Follow the prompts to deploy.

## Step 6: Configure Custom Domain (Optional)

### For GitHub Pages:
1. Go to repository **Settings** > **Pages**
2. Enter your custom domain
3. Follow DNS configuration instructions

### For Vercel:
1. Go to project **Settings** > **Domains**
2. Add your custom domain
3. Configure DNS records as instructed

## Automated Deployments

Both platforms support automated deployments:

- **GitHub Pages**: Automatically deploys on every push to `main` branch via GitHub Actions
- **Vercel**: Automatically deploys on every push to any branch (creates preview deployments)

## Updating Your Portfolio

To update your portfolio:

1. Make changes to files locally
2. Commit and push:
   ```bash
   git add .
   git commit -m "Update portfolio"
   git push
   ```
3. Both GitHub Pages and Vercel will automatically redeploy

## Troubleshooting

### GitHub Pages not updating?
- Check the **Actions** tab for any errors
- Ensure the workflow file is in `.github/workflows/deploy.yml`
- Verify GitHub Pages is set to use GitHub Actions as source

### Vercel deployment failing?
- Check the deployment logs in Vercel dashboard
- Ensure `vercel.json` is in the root directory
- Verify all file paths are correct

### Profile picture not showing?
- Replace the placeholder image URL in `index.html`
- Upload your image to a hosting service (GitHub, Imgur, etc.)
- Update the `src` attribute in the `<img>` tag

## Support

For issues or questions:
- GitHub Pages: [GitHub Docs](https://docs.github.com/en/pages)
- Vercel: [Vercel Docs](https://vercel.com/docs)
