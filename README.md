# Stanley Price Finder (offline-capable)

Searchable catalogue (w.e.f. 1 June 2026): price, price after 10% discount, GST 18% on the discounted price, and total.

## Put it online with GitHub Pages (5 minutes)
1. Create a free GitHub account and click **New repository**. Name it e.g. `price-finder`. Choose **Public** (free Pages needs public unless you have a paid plan).
2. Click **uploading an existing file**, drag in ALL files from this folder (index.html, sw.js, manifest.webmanifest, both icon PNGs), then **Commit changes**.
3. Go to **Settings → Pages**. Under *Branch* pick `main` and `/ (root)`, then **Save**.
4. After about a minute your link appears: `https://<your-username>.github.io/price-finder/`
5. Share that link with your team.

## On every phone / iPad / laptop (do this once, on Wi‑Fi)
1. Open the link. Wait for the yellow **Offline ready** tag at the top.
2. iPhone/iPad: Safari → Share → **Add to Home Screen**. Android: Chrome menu → **Install app** / **Add to Home screen**. Laptop: Chrome/Edge install icon in the address bar.
3. Open it once from the home-screen icon. After that it works with no internet and starts instantly on weak signal.

## Updating prices later
Replace `index.html` in the repo with a new one, and change `pf-v1` to `pf-v2` in `sw.js`. Devices pick up the update the next time they open it with internet.

Note: a public repo is visible to anyone who has the link. Your prices are inside the page, so only share the link with your team.
