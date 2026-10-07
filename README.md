# JNKWatch — Showcase website

Private, static showcase site for the JNKWatch project (open-source round smartwatch).

**Separate from the firmware repo on purpose** — this repo holds only the marketing/landing
page; the watch firmware, emulator and Android app live in the (open-source) JNKWatch repo.

## Stack
100% static — plain HTML, CSS and vanilla JS. No build step, no framework, no dependencies.
The only external resource is a Google Fonts `<link>` (with a system-font fallback).

```
index.html        single-page site (all sections)
styles.css        design system + layout
app.js            scroll-reveal, mobile nav, live clock
assets/img/       rendered watch screenshots (swap in real photos anytime)
```

## Develop / preview
```bash
cd jnkwatch-site
python3 -m http.server      # then open http://localhost:8000
```
All paths are relative, so the folder is portable — it can be served by Apache, GitLab
Pages, or opened directly via `file://`.

## Deploy
Drop the folder behind any static web server. No server-side code required.
