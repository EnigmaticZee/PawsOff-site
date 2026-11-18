# Paws Off website

The website for Paws Off, live at https://trypawsoff.app/.

| Files | What they are |
| --- | --- |
| `index.html`, `media/`, `images/`, `og.png` | The page, its pictures and the link preview card |
| `download/` | The download page: buyers land here after checkout, and the purchase email links to it. Starts the right download for Mac or Windows |
| `install.sh`, `install.ps1` | One-line installers (not shown on the page; still tested weekly) |
| `keys/cancelled.txt` | Cancelled licence key numbers (refunds), read by the app once a week |

Every push to `main` publishes the site (`.github/workflows/site.yml`). The installers are tested on
clean Mac and Windows machines weekly and whenever they change (`.github/workflows/installers.yml`).

© 2026 Polite Owl
