# Glen Fullerton — Portfolio (Netlify + GitHub)

Single-page portfolio (`index.html`) with one‑click PDF export (html2canvas + jsPDF). Pre-configured for Netlify hosting with `netlify.toml` (no build step).

## Quick Start

```bash
# Initialize repo locally
git init
git add .
git commit -m "Initial commit: portfolio page with smart PDF export"
git branch -M main

# Create GitHub repo and push (replace placeholders)
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Deploy to Netlify (UI)

1. Go to https://app.netlify.com → **Add new site** → **Import an existing project**.
2. Choose **GitHub**, select your repo.
3. **Build command**: _(leave blank)_  
   **Publish directory**: `.`
4. **Deploy site**.

You’ll get a URL like `https://<yoursite>.netlify.app`.

### Custom domain (optional)
- **Site settings → Domain management → Add domain** → follow DNS instructions.
- Enable HTTPS.

## Verify
- LinkedIn chip → `https://www.linkedin.com/in/glenrfullerton`
- Download PDF → `Glen_Fullerton_Portfolio.pdf` (no blank first/last page)
- Expanded project Deep‑dives render fully (smart page breaks)

## Notes
- If you later adopt a generator (e.g., Hugo), update `netlify.toml` accordingly.
