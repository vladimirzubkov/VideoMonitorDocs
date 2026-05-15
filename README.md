# VideoMonitor Help (public site)

Static user documentation for [VideoMonitor](https://github.com/vladimirzubkov/VideoMonitor).

**Live site:** [https://vladimirzubkov.github.io/VideoMonitorDocs/](https://vladimirzubkov.github.io/VideoMonitorDocs/)

## How content is published

Markdown and Docusaurus sources live in the private **VideoMonitor** repo under `Documentation/`. On push to `develop` / `main`, the workflow `.github/workflows/deploy-docs.yml` builds the site and pushes the result to the **`gh-pages`** branch of this repository.

You do not need to copy files here by hand.

## One-time GitHub setup

1. **Deploy key** (write) on this repo (`VideoMonitorDocs` → Settings → Deploy keys).
2. **Secret** `DOCS_DEPLOY_KEY` in the private **VideoMonitor** repo (private key contents).
3. **Pages:** this repo → Settings → Pages → **Deploy from a branch** → branch **`gh-pages`** → folder **`/ (root)`**.

After the first successful workflow run, wait 1–2 minutes and open the live URL above.

## Local preview

Edit docs in `VideoMonitor/Documentation/` and run `npm run start` there (see private repo).
