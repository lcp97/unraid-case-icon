# Unraid Case Icon — Jonsbo N6

Custom case icon for **Jonsbo N6** in the native Unraid style: flat monochromatic silhouette on a transparent background, no gradients or shadows.

Two color variants are included so the icon looks right on every Unraid theme.

## Files

| File | Variant | Use with themes |
|---|---|---|
| `rivoli3-server-case.png` | White | Black, Azure (dark themes) |
| `rivoli3-server-case.svg` | White (vector) | — |
| `rivoli3-server-case-scura.png` | Dark (`#262626`) | White, Gray (light themes) |
| `rivoli3-server-case-scura.svg` | Dark (vector) | — |

> **Why two variants?** Unraid's custom case icon is a plain PNG — it doesn't adapt its color to the active theme the way the built-in webfont icons do. Pick the variant that contrasts with your theme's background.

## Installation

1. Go to **Settings → Display Settings → Case Model → Custom**
2. Upload the `.png` that matches your theme (see table above)
3. Done — the icon appears on the Dashboard immediately

On the filesystem the file lands at `/boot/config/plugins/dynamix/case-model.png`.

## What it shows

The icon reproduces the front panel of the Jonsbo N6:

- Upper ventilation mesh panel
- Command strip with fan selector, USB-A, reset pinhole, USB-C, power button, status LED and nine disk-activity LEDs
- Lower diagonal-slat ventilation panel
- Two feet

## Building from source

The icon is generated programmatically with a Python script. The SVG is "flattened" — explicit circles, rects and paths only, no `<pattern>` or `<mask>` — for maximum renderer compatibility.

## License

Public domain — use however you like.
