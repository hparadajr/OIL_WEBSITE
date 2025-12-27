# Website preview and GitHub Pages

A small static site that previews `ai-integration.txt` lives in the `docs/` folder.

Preview locally:

```bash
cd docs
python3 -m http.server 8000
# then open http://localhost:8000
```

To deploy on GitHub Pages:

1. Go to your repository Settings → Pages
2. Set "Source" to the branch you want (e.g., `main`) and set the folder to `/docs`
3. Save — your site will be published at `https://<your-username>.github.io/<repo-name>/` (it may take a minute to appear).

Notes:
- The TXT file is embedded as preformatted text in `index.html` so the file content is visible but scripts are not executed.
- The raw TXT file is available at `docs/ai-integration.txt` and can be downloaded from the site.
