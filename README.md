# Harshavardhan Gowda — Research Portfolio

Live at: **https://harshavardhan-gowda19.github.io/portfolio**

Personal research portfolio site built with vanilla HTML/CSS/JS. No frameworks, no dependencies.

## To edit content

On the live site, type `hg19` anywhere on the page (not in a text field) → enter the admin password → Portfolio Editor panel opens.

All edits are saved to your browser's `localStorage` instantly.

## To deploy changes

```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Actions will automatically rebuild and deploy to GitHub Pages within ~60 seconds.

## Structure

```
index.html      ← the entire site (single file)
.github/
  workflows/
    deploy.yml  ← auto-deploy on push to main
```
