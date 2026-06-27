# Baby Registry — Nayeli & Gabriel's Baby Fund

Static 1-pager. No build step, no dependencies. Just open `index.html` in a browser.

---

## Files

```
index.html      — all markup and inline JS
style.css       — all styles
images/         — drop assets here
```

## Images

| File | Used for |
|------|----------|
| `Animals-Narrow.png` | Header banner on mobile |
| `Animals-Wide.png` | Header banner on 1000px+ |
| `Polaroids-Narrow.png` | Footer photo strip on mobile |
| `Polaroids-Wide.png` | Footer photo strip on 1000px+ |
| `Scallop Border.png` | Sticky decorative top border |
| `envelope.png` | Icon inside CTA box |
| `favicon.png` | Browser tab + iOS home screen icon (180×180px) |

## Editing copy

**English/Spanish text** is in the `translations` object at the bottom of `index.html`. The HTML itself holds the default English — keep both in sync.

The Zelle number is hardcoded in two places — the visible `<strong>` tag and the `writeText('9154493373')` call in the script.

## Breakpoints

- **Mobile (default):** max ~393px layout, narrow images, page gap 0
- **1000px+:** wide images, main section max-width 700px, page gap 16px

## Fonts

Loaded from Google Fonts — requires internet connection to render correctly.
- `Maname` — H1
- `Hanken Grotesk` (500, 700, 800) — everything else

## Deploying

Push to `main` on GitHub → auto-deploys to `baby-registry.nayeliperez.com`.

```bash
git add -A
git commit -m "your message"
git push
```
