# FloWorx Microsoft Identity Association

This repo hosts the `.well-known/microsoft-identity-association.json` file required for Microsoft publisher verification.

## Steps to publish with GitHub Pages
1. Push this repo to GitHub (e.g., `floworx-identity`).
2. Go to repository **Settings → Pages**.
3. Under "Build and Deployment", select:
   - Source: `Deploy from branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Save. You’ll get a URL like:
   `https://<your-username>.github.io/floworx-identity/.well-known/microsoft-identity-association.json`
5. Add a redirect from your Squarespace domain to the GitHub Pages URL if Microsoft requires your own domain.

