# Mixd HTTP server

Mixd is a minimal development HTTP server optimized for serving static HTML files with optional password protection, auto-reload, and integration with Cloudflared tunnels.

---

## Features

- Easy to run development server for HTML/CSS/JS projects
- Optional password protection with random or custom credentials
- Auto-reload support (enabled by default)
- Logs with different verbosity levels
- Serve directory listings with nice UI
- Launch Cloudflared tunnel for public URL access
- Open browser automatically on start

---

## Requirements

- Python 3.8+
- `rich` Python package (`pip install rich`)
- Optional: `cloudflared` installed and available.

---

## Installation

Clone or download this repo, then run:

```bash
pip install rich
