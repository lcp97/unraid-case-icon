# Unraid Case Icons — Jonsbo N-Series

Custom case icons for the **Jonsbo N-series NAS cases** (N2, N3, N4, N5, N6) in the native Unraid style: flat monochromatic silhouettes on a transparent background, no gradients or shadows.

Two color variants per model so the icon looks right on every Unraid theme.

## Files

### Jonsbo N2

| File | Variant | Use with themes |
|---|---|---|
| `jonsbo-n2-case.png` | White | Black, Azure (dark themes) |
| `jonsbo-n2-case-scura.png` | Dark (`#262626`) | White, Gray (light themes) |

### Jonsbo N3

| File | Variant | Use with themes |
|---|---|---|
| `jonsbo-n3-case.png` | White | Black, Azure (dark themes) |
| `jonsbo-n3-case-scura.png` | Dark (`#262626`) | White, Gray (light themes) |

### Jonsbo N4

| File | Variant | Use with themes |
|---|---|---|
| `jonsbo-n4-case.png` | White | Black, Azure (dark themes) |
| `jonsbo-n4-case-scura.png` | Dark (`#262626`) | White, Gray (light themes) |

### Jonsbo N5

| File | Variant | Use with themes |
|---|---|---|
| `jonsbo-n5-case.png` | White | Black, Azure (dark themes) |
| `jonsbo-n5-case-scura.png` | Dark (`#262626`) | White, Gray (light themes) |

### Jonsbo N6

| File | Variant | Use with themes |
|---|---|---|
| `rivoli3-server-case.png` | White | Black, Azure (dark themes) |
| `rivoli3-server-case-scura.png` | Dark (`#262626`) | White, Gray (light themes) |

> **Why two variants?** Unraid's custom case icon is a plain PNG — it doesn't adapt its color to the active theme the way the built-in webfont icons do. Pick the variant that contrasts with your theme's background.

SVG source files are also included for each model.

## Installation

1. Go to your Unraid **Dashboard** and click the case icon at the top
2. Select **Custom** and upload the `.png` that matches your theme (see tables above)
3. Done — the icon appears immediately

On the filesystem the file lands at `/boot/config/plugins/dynamix/case-model.png`.

## What the icons show

Each icon reproduces the front panel of the corresponding case:

- **N2** — smooth top panel, command strip (USB-A, USB-C, power), diagonal ventilation slats
- **N3** — split front: left panel with horizontal ventilation slits, right side with mesh top, command strip, and diagonal slats
- **N4** — walnut wood panel (upper) with power button and USB-A, dot mesh grid (lower)
- **N5** — large mesh panel (upper), command strip (power, USB-A, USB-C, 7 LEDs), horizontal wood slats (lower)
- **N6** — mesh panel (upper), command strip (USB-A, USB-C, power, 9 LEDs), diagonal ventilation slats (lower)

## Building from source

All icons are generated programmatically with Python + pycairo. The SVGs are "flattened" — explicit circles, rects and paths only, no `<pattern>` or `<mask>` — for maximum renderer compatibility.

## License

Public domain — use however you like.
