# GitHub Pages Setup Instructions

This repository is configured for GitHub Pages deployment from the `docs/` directory.

## Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Build and deployment**:
   - **Source**: Select "GitHub Actions"
4. The workflow will automatically deploy on push to the `main` branch

## Structure

- `docs/index.html` - Main HTML page (placeholder ready for content)
- `docs/.nojekyll` - Prevents Jekyll processing
- `.github/workflows/pages.yml` - Automated deployment workflow

## Adding Content

Simply edit `docs/index.html` with your desired HTML content. The page will automatically deploy when changes are pushed to the main branch.

## Manual Deployment

You can also manually trigger the deployment:
1. Go to **Actions** tab
2. Select "Deploy GitHub Pages" workflow
3. Click "Run workflow"
