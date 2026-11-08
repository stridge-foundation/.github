# Brand rasters

PNG versions of the Stridge marks, for the surfaces that cannot use the SVGs.

| File | Size | |
| --- | --- | --- |
| `stridge-lockup-black.png` | 601×160 | mark + logotype, on a light ground |
| `stridge-lockup-white.png` | 601×160 | same, on a dark ground |
| `stridge-mark-black.png` | 512×512 | mark alone, on a light ground |
| `stridge-mark-white.png` | 512×512 | same, on a dark ground |

Each is transparent RGBA at twice its intended display size, so it stays sharp on a retina screen.

Prefer the vector originals anywhere they render.

## Rules

Both inks are official assets, so picking the one that contrasts with the surface behind it is not a
recolour — but that is the only choice available. Do not recolour, rotate, distort, or add effects to
the marks, and do not regenerate them at a different aspect ratio.

They were rasterised from the SVGs published on [stridge.com/brand](https://stridge.com/brand) with
[resvg](https://github.com/linebender/resvg): the lockups at 160 tall (their viewBox is `8438×2246`),
the marks at twice their `256×256` viewBox. Regenerate the same way if the vectors change; do not
hand-edit the PNGs.
