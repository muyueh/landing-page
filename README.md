# Landing Page Theme

This repository includes the Agnes landing page theme. GitHub Pages deployment is configured via GitHub Actions to build the theme assets and publish the contents of the `agnes` folder.

## Local preview
From the `agnes` directory, install dependencies and build the compiled assets:

```bash
npm install
npm run build
```

Then open `agnes/index.html` in a browser to preview the static site. The build places compiled assets in the `agnes/dist` directory.

## Deployment
Push changes to `main`, `master`, or `work` to trigger the **Deploy to GitHub Pages** workflow. The workflow installs dependencies, builds the theme (including `dist` assets), uploads the `agnes` directory, and deploys it to GitHub Pages. You can also run the workflow manually from the **Actions** tab.
