# ⚡ Ather Cost Tracker

A mobile web app to log your Ather 450X rides and charging, and see how much you save vs petrol — including how much of the scooter's cost you've recovered.

Works fully offline after first load. All data stays on your phone (browser storage).

## Files

- `index.html` — the whole app
- `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` — make it installable + offline
- `preview.webp` — your reference screenshot (not needed for the app; you can skip uploading it)

## Put it on GitHub Pages (one-time, ~5 min)

1. Go to [github.com](https://github.com) → sign in → **+** → **New repository**.
2. Name it e.g. `ather-tracker`, keep it **Public**, click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, then **Commit changes**.
4. Repo → **Settings** → **Pages** → under *Branch* choose `main` and `/ (root)` → **Save**.
5. Wait ~1 minute. Your app is live at:
   `https://YOUR-USERNAME.github.io/ather-tracker/`

## Install on your phone

1. Open that URL in **Chrome** on your phone.
2. Menu (⋮) → **Add to Home screen** → **Install**.
3. It now opens full-screen like a native app, works offline, and keeps your data.

## Using the app

- **Settings first**: set your electricity rate (₹/unit), current petrol price, battery kWh (3.7), petrol mileage to compare (50 km/l), and scooter total cost (₹2,26,211).
- **Rides**: copy numbers from the Ather app's Ride Details — distance, duration, efficiency (km/unit), Eco/Ride split. Avg speed auto-calculates.
- **Charging → Home**: enter battery % from → to; units and cost auto-fill from your battery size and rate (editable). Or type units directly from your meter.
- **Charging → Fast**: enter units and amount paid at Ather Grid.
- **Dashboard**: total savings vs petrol, ₹/km, monthly EV-vs-petrol chart, and the cost-recovery bar.

## Your data

- Stored only in your phone's browser — nothing is uploaded anywhere.
- **Settings → Backup data (JSON)** now and then. Restore it on any device with **Restore from backup**.
- Clearing the browser's site data deletes the log, so keep a backup.

## Updating the app later

Edit/replace `index.html` in the GitHub repo and commit — the app picks up the new version next time you open it with internet.
