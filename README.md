
# Academic Homepage (GitHub Pages)

China-friendly static site template for an academic homepage. No external CDNs, system fonts only.

## Quick Start

1) Rename the repo to `<your-username>.github.io` (user site) **or** any name (project site).
2) Put these files at the root of the repo.
3) Commit + push to `main`.

### Enable GitHub Pages
- Go to Settings → Pages.
- **Source**: `Deploy from a branch`.
- **Branch**: `main` (root).

GitHub will build and serve your site at:
- `https://<your-username>.github.io/` (user site), or
- `https://<your-username>.github.io/<repo-name>/` (project site).

### Custom Domain (Optional)
- Buy a domain (e.g., from Namecheap/Alibaba Cloud).
- Add `CNAME` record pointing to `<your-username>.github.io`.
- Create a file named `CNAME` in the repo root containing your domain, e.g. `yourdomain.com`.
- In Settings → Pages, add your domain and enable HTTPS.

### China Performance Tips
- Avoid Google Fonts/YouTube/Drive embeds.
- Host PDFs/images locally under `/assets`.
- Optimize images (≤ 150KB when possible).
- If access is slow domestically, mirror the repo to **Gitee Pages**.
  - Keep assets identical; avoid external CDNs.

### Editing
- Replace placeholder text in `index.html`.
- Put your headshot at `assets/headshot.jpg` and update the `<img>` src.
- Put your CV at `assets/cv.pdf` and link it.
- Add more sections as needed.

### Jekyll (Optional)
You can turn this into a Jekyll site by adding `_config.yml` and layout files, but plain static HTML works fine and builds instantly.
