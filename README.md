# SPEQ GitHub Pages site

Static public site for SPEQ MVP v1.0.0.

Production URL:

```text
https://speq-tms.github.io/
```

## Local structure

```text
/
  index.html
  quickstart.html
  install.html
  ci-secrets.html
  examples.html
  assets/
    styles.css
```

No package manager, generator, or build step is required for MVP v1.0.0.

## GitHub Pages setup

After changes are merged to `main` and pushed:

1. Open the `speq-tms.github.io` repository on GitHub.
2. Go to `Settings` -> `Pages`.
3. Under `Build and deployment`, set:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
4. Save the settings.
5. Wait for the Pages deployment to finish.
6. Verify `https://speq-tms.github.io/`.

No custom domain is required for MVP v1.0.0.
