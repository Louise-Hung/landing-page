# Stride - Bootstrap 5 HTML template
A simple but clean Bootstrap 5 HTML template from https://templatedeck.com

## GitHub Pages deployment
This repository ships with a GitHub Actions workflow that publishes the site to GitHub Pages whenever changes are pushed to the `main` branch or the workflow is manually triggered.

1. Ensure GitHub Pages is configured to use the **GitHub Actions** source in your repository settings.
2. The workflow at `.github/workflows/deploy.yml` checks out the repository, prepares the Pages environment, uploads the static site files from the repository root, and deploys them to Pages.
3. Once the workflow completes, the live site URL will appear in the deployment summary for the run.
