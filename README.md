# ArcelorMittal — Inspiration Session Demo Pages

Self-contained HTML demos for the ArcelorMittal management inspiration session.
Designed to run full-screen on a mobile device (via "Add to Home Screen" in
Safari or a wrapper app).

## Structure

| Path | What it is |
|------|-----------|
| `index.html` | Landing / **select page** — pick which demo to launch. This is the URL to open on the device. |
| `fieldvisit/` | Field Visit Agent: a Key Account Manager's mobile app for a steel-supply customer (Meridian Infrastructure) — AI pre-meeting briefing, voice & photo visit notes, account 360, and Google Maps navigation. |

Each demo is a scripted, self-contained simulation — no backend, no login.

## Publishing (GitHub Pages)

Served from the repository **root** on `main`:

1. Push this folder to a GitHub repo.
2. Repo **Settings → Pages** → Source: **Deploy from a branch** → Branch: `main` / `(root)`.
3. Live at `https://<user>.github.io/<repo>/` — open on the device.

> **Note:** the "Take image" camera capture only works over **HTTPS** (GitHub
> Pages is HTTPS, so it works there — not over `file://`).

## Running locally

```
python3 -m http.server
```
