# BTC Position Tracker (PWA) — GitHub Pages

Single-file HTML app that tracks BTC lots, fetches live price (Coinbase → Binance → CoinDesk fallback), and shows per-lot P/L, totals, average entry, ROI. Includes PWA (Install + Offline).

## How to publish to GitHub Pages
1. Create a new **public** repo named **jijmij**.
2. Upload `index.html` and `.nojekyll` to the repository root.
3. Go to **Settings → Pages**:
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/** (root)
4. Open the site:

   `https://<your-username>.github.io/jijmij/`

## PWA tips
- First load the page, click **Enable Offline** (registers Service Worker), then use **Install App** when the browser shows the prompt.
- Works best over **HTTPS** (GitHub Pages provides HTTPS).

## Data
- Lots are saved in `localStorage` on your device.
- You can **Save JSON**/**Load JSON** to back up/restore.

