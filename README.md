# GitHub Pages Publish Pack

Prepared: 2026-03-09T00:37:46-04:00
Related opportunity: opp-btcfi-map-001
Related experiment: exp-btcfi-sample-001

## What this folder contains
- `index.md` — GitHub Pages-ready canonical public page
- `_config.yml` — minimal Jekyll config for GitHub Pages

## Fastest publish path
1. Create a new public GitHub repository.
2. Copy the contents of this folder into the repo root.
3. Commit and push to `main`.
4. In GitHub, enable **Settings → Pages → Deploy from a branch** using `main` and `/ (root)`.
5. Wait for the site to build, then note the public URL.
6. Replace `{SET_PUBLIC_URL_AFTER_PUBLISH}` inside `index.md` with the real public URL and push once more.
7. Update the launch-copy placeholders in:
   - `reports/2026-03-08-btcfi-v1-launch-assets.md`
   - any downstream Paragraph / Stacker News post drafts

## Why this pack exists
No public host, git remote, or Pages-enabled repo is currently configured in this workspace. This pack reduces the next publish step to a simple repo push plus Pages enablement.
