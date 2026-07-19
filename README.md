# GitHub Pages Deployment

A simple static website deployed automatically to GitHub Pages using GitHub Actions.

## Project Contents

- `index.html` - The static website page that says "Hello, GitHub Actions!"
- `.github/workflows/deploy.yml` - GitHub Actions workflow that deploys the site.

## Deployment Behavior

- The workflow runs on every push to the `main` branch.
- It only triggers when `index.html` is changed.
- When triggered, it deploys the website to GitHub Pages.

## GitHub Pages URL

Your site will be available at:

`https://<username>.github.io/gh-deployment-workflow/`

Replace `<username>` with your GitHub username.

## Project URL

`https://github.com/<username>/gh-deployment-workflow`
