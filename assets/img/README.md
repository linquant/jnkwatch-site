# Site images

Drop real photos here by **overwriting these files** — the HTML references them by name,
so no markup changes are needed.

| File        | Where it shows            | Current source            | Suggested replacement                         |
|-------------|---------------------------|---------------------------|-----------------------------------------------|
| `clock.png` | Hero device preview (OG)  | `docs/screenshots/clock.png` | A close-up of the real clock face, ~1:1    |
| `faces.png` | "The deck" showcase       | `docs/screenshots/faces.png` | Photo/render grid of the faces (wide)      |
| `frame.png` | Hardware section          | `frame.png` (repo root)      | A real photo of the watch on the board/wrist |

Tips for drop-in replacements:
- Keep the **same filename** (or update the `<img src>` in `../../index.html`).
- Figures use `aspect-ratio` boxes, so mismatched dimensions won't break the layout —
  but matching the rough aspect ratio looks best.
- Optimize before committing (PNG/JPG, ideally < 300 KB each).
