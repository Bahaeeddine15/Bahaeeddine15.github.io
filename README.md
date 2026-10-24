# Bahae Eddine Mekrane · Portfolio

Personal portfolio in English and French. Plain HTML and CSS, no build step, hosted on GitHub Pages.

```
index.html        English version (site root)
fr/index.html     French version
assets/photo.jpg  your photo (add it yourself, see assets/README.md)
CNAME             your custom domain (add it once you have one)
```

## Publish on GitHub Pages

1. Settings → Pages.
2. Source: **Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
3. After a minute the site is live at `https://bahaeeddine15.github.io/`.

## Add a custom domain

1. Settings → Pages → Custom domain: enter your domain (for example `bahae.dev`) and Save. GitHub creates the `CNAME` file.
2. At your domain registrar, add these DNS records:

| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | bahaeeddine15.github.io |

3. Wait for DNS (up to 24 hours), then tick **Enforce HTTPS** in Settings → Pages.

## Edit the content

Text lives directly in `index.html` (English) and `fr/index.html` (French). When you change one, change the other too.
