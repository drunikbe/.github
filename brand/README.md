# DRUNIK brand assets

Canonical logo files for the DRUNIK BV brand.

## Files

| File | Use |
|------|-----|
| `favicon.svg` | Square app/site favicon. White mark on black background. 1000×1000 viewBox. |
| `favicon.png` | Raster fallback for `favicon.svg`. |
| `logo.png` | Full-resolution wordmark. Use when you need the highest fidelity. |
| `logo-clean-black.png` | Wordmark only, black on transparent. Use on light backgrounds. |
| `logo-clean-white.png` | Wordmark only, white on transparent. Use on dark backgrounds. |
| `logo-bg-black.png` | Wordmark on a black background tile. |
| `logo-bg-white.png` | Wordmark on a white background tile. |

## Light/dark aware embedding

Use a `<picture>` element so the right variant shows in each theme:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/drunikbe/.github/main/brand/logo-clean-white.png">
  <img src="https://raw.githubusercontent.com/drunikbe/.github/main/brand/logo-clean-black.png" alt="DRUNIK" width="280">
</picture>
```

## Source files

The Affinity (`logo.af`) and Illustrator (`logo.ai`) source files are not committed here. Ask in the design channel if you need them.
