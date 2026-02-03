# mfb-calculator

## 📦 Deploy to GitHub Pages ✅

This repository can be published as a **GitHub Pages** project site.

- A GitHub Actions workflow has been added at `.github/workflows/gh-pages.yml` that will automatically publish the repository root to the `gh-pages` branch when you push to `main` (or run the workflow manually via *Actions → Deploy*).
- A `.nojekyll` file is included so files are served as-is (Jekyll will be disabled).

After the workflow runs, enable GitHub Pages in the repository settings (if not auto-enabled) and set the Source to the `gh-pages` branch and folder `/ (root)`. Your site will be available at:

```
https://<github-username>.github.io/<repo-name>/
```

Replace `<github-username>` and `<repo-name>` with your GitHub username and repository name.

---

If you prefer not to use Actions, you can also enable GitHub Pages directly in the repository settings and serve from `main` (root) instead.
