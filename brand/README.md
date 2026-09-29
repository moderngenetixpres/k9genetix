# K9 Genetix — brand assets (locked 2026-09-29)

Emblem: deep navy disc, royal-blue outer ring, royal/navy DNA helix with heart-shaped top and bottom loops,
silver/chrome rungs with ball ends, small silver paw at the center twist.

| File | Size | Notes |
|------|------|-------|
| `logo-k9-blue-1024.png` | 1024² | Master, transparent outside the circle |
| `logo-k9-blue-512.png` | 512² | Transparent |
| `logo-k9-blue-180.png` | 180² | Transparent (site header/footer) |
| `apple-touch-icon.png` | 180² | Opaque on `#050608` (iOS) |
| `favicon.ico` | 16/32/48 | 16 & 32 use a tighter crop with a redrawn royal ring for legibility |
| `favicon-16.png`, `favicon-32.png`, `favicon-48.png` | | PNG favicons |
| `og-k9-blue-emblem.png` | 1200×630 | Social share card |

Source render was ~5% vertically stretched (ellipse 1012×1065 px); it was resampled to a true circle
(fit residual 0.56 px) before cropping.

## Palette (sampled from the source with PIL)

| Token | Hex | Sampled from |
|-------|-----|--------------|
| Black base | `#050608` | site base (source bg ≈ `#010101`–`#020202`) |
| Groove black-navy | `#00020e` | inner dark ring |
| Deep navy | `#010c27` | disc field |
| Navy band | `#030f2a` | band inside outer ring |
| Navy mid | `#0c347e` | helix shadow side |
| Royal ring | `#2b60b3` | outer ring (p90) |
| Royal (helix) | `#335dae` | helix body median |
| Royal highlight | `#4174c7` | outer ring highlight (p99) |
| Royal bright | `#527dcf` | helix highlight |
| Silver | `#afb1ba` | rungs/paw median |
| Chrome highlight | `#e1e5ec` | rung/ball specular |
| Silver shadow | `#74787f` | rung/ball shadow |

Web-only text tints (for WCAG contrast on black): `#6f97ea` (≈7:1 on `#050608`), `#7ea2ec` (≈8:1).
Primary button: `#4174c7 → #2b60b3` gradient with white text (≥4.6:1).
