# Azka Fuaad — Portfolio

This is a simple static portfolio site. Below are commands to publish this folder to GitHub Pages.

Prerequisites:
- Git installed
- (Optional) GitHub CLI `gh` installed and authenticated

Quick publish using Git and GitHub CLI:

1. Open PowerShell in this folder (`my portfolio`).

2. Initialize, commit and create a GitHub repo, then publish:

```powershell
git init
git add .
git commit -m "Initial portfolio commit"
# Replace <USERNAME> and <REPO> with your GitHub username and desired repo name
gh repo create <USERNAME>/<REPO> --public --source=. --push
gh pages create --source=main
```

After deployment the site will be available at:

```
https://<USERNAME>.github.io/<REPO>/
```

If you don't have `gh`, you can create a repo on GitHub.com, then run:

```powershell
git remote add origin https://github.com/<USERNAME>/<REPO>.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in the repository Settings → Pages and choose branch `main` → Save.

If you want, I can run these commands locally for you — I won't push without your confirmation.
