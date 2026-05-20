# ytm>labs — Brand Assets

Public-facing brand assets for ytm>labs UG (i.G.). Hosted via raw.githubusercontent.com so they can be embedded in emails, third-party platforms, and other tools that need a stable URL.

**Source of truth:** The full brand documentation lives in the private `ObsidianYtml/ytmlabs` vault under `wiki/concepts/frameworks/brand-guidelines.md`. This repo just mirrors the public assets.

## Layout

```
logos/                       Logo files in multiple variants
  ytmlabs-logo.svg           Wide vector (primary)
  ytmlabs-logo-wide.png      960x240 PNG
  ytmlabs-logo-transparent.png  Transparent BG variant
  ytmlabs-logo-square.png    800x800 square
  logo-circle.svg            Circle variant
  logo-192.png               Favicon / app icon

email-signature/             Email signature templates
  signature.html             HTML signature (Gmail/Outlook compatible)
  signature.txt              Plaintext fallback
```

## Brand colors

- **Orange** (primary): `#F97316`
- **Cursor Gray** (logo bg): `#e5e5e5`
- **Text** (light bg): `#1a1a1f`
- **Dark BG**: `#1a1a1f`

## Typography

- **Headlines + Logo**: Inter Bold (700-800)
- **Body**: Inter Regular (400)
- **Code**: JetBrains Mono Regular (400)

## Hosting

Files are served via GitHub Raw at:
```
https://raw.githubusercontent.com/YtmL-MagY/brand-assets/main/<path>
```

**Future:** Once `ytml.ai` is live, these will move to `assets.ytml.ai/...` (URLs in this repo's consumers will need a one-line swap).
