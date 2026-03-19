# Man Power — Universal Shift Management

**Live:** [mp.vkstech.com](https://mp.vkstech.com)

## Setup

1. Upload all 5 files to your GitHub repo root
2. Enable GitHub Pages (Settings → Pages → Source: main branch)
3. Point your domain `mp.vkstech.com` to GitHub Pages
4. Open the app → Super Admin first login will ask you to set password

## Files

| File | Purpose |
|------|---------|
| `index.html` | Complete app (single file) |
| `manifest.json` | PWA manifest for install |
| `sw.js` | Service Worker for offline & caching |
| `icon-192.png` | App icon 192x192 |
| `icon-512.png` | App icon 512x512 |

## Roles

- **Super Admin** (ID: 8929397949) — sees all managers & workers
- **Manager** — registers via OTP, manages team & shifts
- **Worker** — added by manager, logs in via OTP → Fingerprint
