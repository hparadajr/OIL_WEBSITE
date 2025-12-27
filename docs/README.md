# OIL_WEBSITE — docs site

This `docs/` folder contains a small static site that previews `ai-integration.txt`.

Preview locally:

```bash
cd docs
python3 -m http.server 8000
# then open http://localhost:8000
```

Deploy on GitHub Pages:

1. In the GitHub repo go to Settings → Pages
2. Under "Source" choose the branch (e.g., `main`) and set the folder to `/docs`
3. Save — your site will be available at `https://<your-username>.github.io/<repo-name>/`

Notes:
- The file is embedded as preformatted text in `index.html` to ensure embedded scripts are not executed.
- The raw TXT is available at `ai-integration.txt` and can be downloaded.
