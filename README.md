# Landing Page Theme

The Agnes landing page theme now lives in the repository root. GitHub Pages is configured to publish the root build output so the site is available at https://muyueh.github.io/landing-page/.

## Local preview
From the repository root, install dependencies and build the compiled assets:

```bash
npm install
npm run build
```

Then open `index.html` in a browser to preview the static site. The build places compiled assets in the `dist` directory, and the compiled files are checked into the repository so GitHub Pages always has the CSS and JS available.

## Deployment
Push changes to `main`, `master`, or `work` to trigger the **Deploy to GitHub Pages** workflow. The workflow installs dependencies from the repository root, builds the theme (including `dist` assets), and deploys the root site bundle to GitHub Pages. You can also run the workflow manually from the **Actions** tab.

The **Branch Pages Preview** workflow still publishes per-branch previews under `branches/<branch-name>` so you can test changes without affecting the main site. The branch index at `/branches/` lists available previews.
