# Orbit Aviation

Public homepage for the Orbit Aviation FS Economy virtual flying group.

**Repo:** https://github.com/parsectv/OrbitAviationFSE_Site.git

## Structure

```
index.html       — Main site (single-file, self-contained)
.cpanel.yml      — cPanel Git Version Control auto-deploy config
.gitignore       — Standard ignores
```

## Deployment

This repo is linked to cPanel via **Git Version Control**.

On every push to `main`, cPanel will automatically copy `index.html` to `public_html/`.

### Manual deploy (cPanel)
1. Log into cPanel
2. Go to **Git Version Control**
3. Find this repo and click **Manage → Deploy HEAD Commit**

## Local development

Single self-contained HTML file — no build step, no dependencies.
Just open `index.html` in a browser.
