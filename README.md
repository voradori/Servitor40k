# Servitor40k — GitHub Pages (Meta app legal URLs)

Static pages for **Threads Servitor** Meta Developer App: Privacy Policy and Data Deletion Instructions.

Not a product website — compliance hosting only.

## Enable GitHub Pages

1. Push this repo to `https://github.com/voradori/Servitor40k`
2. GitHub → **Settings** → **Pages**
3. **Build and deployment** → Source: **Deploy from a branch**
4. Branch: **main** (or **master**), folder: **/ (root)**
5. Save. After 1–3 minutes the site is live.

## URLs for Meta App Dashboard

Replace after Pages is enabled (check **Settings → Pages** for the exact URL):

| Field | URL |
|-------|-----|
| **Privacy Policy URL** | `https://voradori.github.io/Servitor40k/privacy.html` |
| **Data Deletion Requests URL** | `https://voradori.github.io/Servitor40k/data-deletion.html` |
| Home (optional) | `https://voradori.github.io/Servitor40k/` |

Verify with [Sharing Debugger](https://developers.facebook.com/tools/debug/) — expect HTTP **200**, no login wall.

## Before submit

- [ ] Pages enabled and both links open in an incognito window
- [ ] Add your contact **email** in `README.md` below and optionally in `privacy.html` / `data-deletion.html`
- [ ] **Deauthorize callback URL** is a real endpoint if Dashboard requires it — do not reuse `data-deletion.html` as a POST callback (see Meta docs)

## Contact (for privacy / deletion requests)

<!-- Replace with your real email for Meta App Review -->
**Email:** `voradoripl@gmail.com`  
**GitHub Issues:** https://github.com/voradori/Servitor40k/issues

## Files

| File | Purpose |
|------|---------|
| `index.html` | Landing with links (avoids 404 on site root) |
| `privacy.html` | Privacy Policy URL |
| `data-deletion.html` | Data Deletion Requests URL |
| `style.css` | Minimal shared styles |

## License

Private operator use. Text may be adapted for your jurisdiction; not legal advice.
