# GitHub Pages Deployment

A simple static website deployed automatically to GitHub Pages using GitHub Actions.

## Project URL

https://roadmap.sh/projects/github-actions-deployment-workflow

## Features

- Automatic deployment to GitHub Pages using GitHub Actions
- Workflow runs only when `index.html` changes
- Static HTML website

## Project Structure

```
.
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

## Deployment

Every push to the `main` branch that modifies `index.html` automatically triggers the GitHub Actions workflow, which:

1. Checks out the repository
2. Configures GitHub Pages
3. Uploads the website files
4. Deploys the site

## Live Website

https://sandeepkumar1703.github.io/gh-deployment-workflow/

## Repository

https://github.com/Sandeepkumar1703/gh-deployment-workflow