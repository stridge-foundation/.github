# Brand rasters

PNG versions of the Stridge marks, for the surfaces that cannot use the SVGs.

| File | Size | |
| --- | --- | --- |
| `stridge-lockup-black.png` | 590×160 | mark + wordmark, on a light ground |
| `stridge-lockup-white.png` | 590×160 | same, on a dark ground |
| `stridge-mark-black.png` | 512×512 | mark alone, on a light ground |
| `stridge-mark-white.png` | 512×512 | same, on a dark ground |

Each is transparent RGBA at twice its intended display size, so it stays sharp on a retina screen.

Prefer the vector originals anywhere they render.

## Rules

Both inks are official assets, so picking the one that contrasts with the surface behind it is not a
recolour — but that is the only choice available. Do not recolour, rotate, distort, or add effects to
the marks, and do not regenerate them at a different aspect ratio.

They were rasterised from the published SVGs with [resvg](https://github.com/linebender/resvg) at
twice the viewBox (`294.96×80` for the lockups, `256×256` for the marks). Regenerate the same way if
the vectors change; do not hand-edit the PNGs.
