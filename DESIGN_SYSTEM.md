# GitHub Profile Visual Design System

## Design direction

**Dark Engineering / Premium 3D**. One consistent navy engineering canvas, cyan as the shared interface language, and distinct red / cyan / violet accent lighting for each project.

## Color tokens

| Token | Hex | Role |
| --- | --- | --- |
| Background | `#070D19` | Shared cover background |
| Surface | `#0D2036` | Card depth and secondary gradients |
| Deep surface | `#071621` | Final gradient stop |
| Primary | `#4BE5DA` | Borders, section labels and technical highlights |
| F1 accent | `#F35467` | Motorsport-only accents |
| Infra accent | `#4BE5DA` | Infrastructure-only accents |
| Aetron accent | `#A980FF` | Fitness-only accents |
| Text | `#F4FAFF` | Primary typography |
| Muted | `#9EC8D7` | Supporting labels |

## Asset template

- Project covers: `1000 × 560` SVG, 16:9-ish fixed canvas (1000:560).
- Section banners: `1200 × 160` SVG, identical type hierarchy.
- Now Building: `1200 × 268` SVG.
- Footer: `1200 × 110` SVG.
- Use a single dark gradient on every cover; retain each subject's accent lighting.
- Main subjects and details stay within frame safe margins; project title lives at x≈43 and y≈150.
- Animated movement is concentrated in the hero and optional F1 GIF preview; featured covers remain static for consistency and reduced visual noise.
- Cards use an identical top rule, rounded border, headline hierarchy and metadata grouping.
- All artwork remains readable on GitHub in light or dark mode, without assuming custom page CSS.

## Content rules

- Project artwork and README text must describe real, checkable project features.
- Current learning focus is not represented as a completed production deployment.
- Repository links used in the public profile must be publicly accessible.
- The animated F1 chibi GIF is preserved in an expandable preview instead of competing visually with the uniform primary cover.

## Assets in active README

- `assets/hero-motion.svg` — introduction
- `assets/projects-spectrum.svg` — selected work heading
- `assets/project-f1.svg` — featured F1 cover
- `assets/project-infra.svg` — infrastructure cover
- `assets/project-aetron.svg` — Aetron cover
- `assets/now-building-spectrum.svg` — DevOps / Cloud focus
- `assets/toolkit-spectrum.svg` — toolkit heading
- `assets/footer-spectrum.svg` — footer
- `f1-chibi-2026.gif` — optional animated preview

Existing unused assets are left untouched for reference. Do not mix their former layouts into the current README.
