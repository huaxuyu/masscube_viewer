# Peak Shape Plotter (GitHub Pages)

**Zero-build, single-file website** to plot RT–Intensity peak shapes from strings like:

```
0.345;1734.0|0.35;0.0|0.356;1540.0|...
```

## Deploy to GitHub Pages (free)
1. Create a new repo on GitHub (e.g., `peak-plotter`).
2. Upload `index.html` (from this folder) to the root of the repo and commit to the **main** branch.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose:
   - Source: **Deploy from a branch**
   - Branch: **main** / **root**
4. Save. Your site will appear at: `https://<your-username>.github.io/<repo-name>/`

## Usage
- Paste data into the textarea in the `rt;intensity|...` format.
- Click **Plot** (or press **Ctrl/Cmd + Enter**).
- Use **Download PNG** for the chart and **Download CSV** for the parsed data.

## Notes
- Font is **Arial**. Y‑axis label spacing avoids overlap with ticks.
- No build tools, only Plotly CDN. Works offline once cached.
