# signal_spatial brand

Official colors for signal_spatial. The values live in [`colors.css`](colors.css).

Dark surfaces stay in the blue range so Chart White text stays readable. Signal Yellow is for fills, markers, and large type on navy. Field Gold is the yellow for small text and icons on light backgrounds.

## Core

| Role | Name | Hex | CSS variable | Use |
| --- | --- | --- | --- | --- |
| Primary | Signal Navy | `#0F2C4C` | `--ss-navy` | Logo, headers, dark surfaces, primary buttons |
| Primary deep | Night | `#071626` | `--ss-night` | Footer, hero edges, highest-contrast dark |
| Secondary | Harbor | `#1B4F72` | `--ss-harbor` | Links, secondary buttons, chart series |
| Accent | Signal Yellow | `#F0C419` | `--ss-yellow` | Highlights, markers, icons and buttons on navy |
| Accent text | Field Gold | `#8C6A00` | `--ss-gold` | Yellow used as text or small icons on light backgrounds |
| Text | Graphite | `#2A3138` | `--ss-graphite` | Body text |
| Muted | Slate | `#5E6A75` | `--ss-slate` | Captions, axes, secondary labels |
| Line | Mist | `#E4E8EC` | `--ss-mist` | Borders, dividers, map chrome |
| Surface | Paper | `#F7F8FA` | `--ss-paper` | Page background |
| On navy | Chart White | `#F8FAFC` | `--ss-white` | Text and icons on navy |

## Map ramps

Sequential, light to dark: `#F7F8FA` → `#D5DCE3` → `#8E9AAB` → `#1B4F72` → `#0F2C4C`.

Paint the feature that should be read first in `#F0C419`. Keep everything else on the navy–gray ramp.

## Use

```css
@import "colors.css";
```

```html
<link rel="stylesheet" href="colors.css">
```
