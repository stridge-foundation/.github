# Brand rasters

PNG versions of the Stridge marks, for the places that cannot use the SVGs.

**These exist for email.** Gmail strips an `<img>` pointing at an SVG and Outlook will not draw one,
so an SVG logo is a blank space in most of the inbox. Every other surface should keep using the
vector originals.

They are served straight from this repository over GitHub's raw CDN, which is why they live here
rather than in a build:

```
https://raw.githubusercontent.com/stridge-foundation/.github/main/brand/stridge-lockup-black.png
```

| File | Size | Use |
| --- | --- | --- |
| `stridge-lockup-black.png` | 590×160 | mark + wordmark, on a light ground |
| `stridge-lockup-white.png` | 590×160 | same, on a dark ground |
| `stridge-mark-black.png` | 512×512 | mark alone, on a light ground |
| `stridge-mark-white.png` | 512×512 | same, on a dark ground |

Each is transparent RGBA at twice its intended display size, so it stays sharp on a retina screen.

## Rules

Both inks are official assets, so choosing between them is not a recolour — but **that is the only
choice available.** Do not recolour, rotate, distort, or add effects to the marks, and do not
regenerate them at a different aspect ratio.

They were rasterised from the published SVGs with [resvg](https://github.com/linebender/resvg) at 2×
the viewBox (`294.96×80` for the lockups, `256×256` for the marks). Regenerate the same way if the
vectors ever change; do not hand-edit the PNGs.

## Consumers

- `stridge-foundation/mailchef` — the transactional email layout, which references the two lockups
  and swaps them by `prefers-color-scheme`.
