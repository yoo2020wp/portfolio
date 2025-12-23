# Hyuntae Portfolio (Static Site)

## Quick start (local preview)
If you have Python installed:
```bash
cd hyuntae-portfolio
python -m http.server 8080
```
Then open: http://localhost:8080

## Deploy to your web server
Upload the entire folder contents to your server's web root (often: /var/www/html).

Minimum required files:
- index.html
- courses.html
- projects.html
- docs.html
- /css
- /js
- /assets

Resume file:
- /assets/Hyuntae_Yoo_Resume.pdf

## Notes
- IP addresses are anonymized by design.
- This is a starter version designed to be edited directly in HTML/CSS.
- When you are ready for CI/CD, we can migrate this structure to a static-site generator (e.g., Eleventy/Astro) and deploy from GitHub.
