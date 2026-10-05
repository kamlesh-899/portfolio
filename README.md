# Kamlesh Mali – Portfolio

Personal site: a single static `index.html` (no build step).

## Deploy (one time)
1. Create an empty repo on GitHub, e.g. `portfolio` (or `<username>.github.io`).
2. In this folder run:
   ```
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo>.git
   git push -u origin main
   ```
3. On GitHub: Settings → Pages → Build and deployment → Source: **GitHub Actions**.
4. The workflow runs on every push to `main`. Live URL: `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` for a `<username>.github.io` repo).

## Update later
Edit `index.html`, then `git add . && git commit -m "Update" && git push`.
