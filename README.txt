
Flowless — One-page site for GitHub Pages
----------------------------------------

Files:
- index.html
- assets/styles.css
- assets/logo.svg

How to deploy:
1. Create a GitHub repo named <your-username>.github.io (recommended for user site) or any repo.
2. Upload all files and folders (or unzip locally and push with git).
3. In GitHub: Settings → Pages → Source → choose 'main' branch, save.
4. Wait a minute and visit: https://<your-username>.github.io/ (or https://<your-username>.github.io/<repo>/ if not a user site).

Notes:
- Contact form uses a mailto fallback (no server) and opens the user's email client.
- Headings use 'Alliance' in CSS; if you want exact Alliance font, upload your webfont and add @font-face in assets/styles.css or change to a web-safe font.
- To use a custom domain, add it in Pages settings and update DNS records at your registrar.
