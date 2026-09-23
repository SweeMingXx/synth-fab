# SYNTH//FAB

**Imagination, materialized.** A self-contained interactive generative fabrication portfolio in `index.html`.

## Open it

Open `index.html` in a modern WebGL browser, or serve the repository with `python3 -m http.server 8000`. No build step, npm dependencies, API keys, or backend. Internet access is required for Tailwind's CDN, Three.js r128, OrbitControls, and Google Fonts. All essential styling is inline, so Tailwind or font outages do not destroy the layout.

## Publish once

1. Open **[Settings → Pages](https://github.com/SweeMingXx/synth-fab/settings/pages)**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. Open **[Actions → Verify and publish SYNTH FAB](https://github.com/SweeMingXx/synth-fab/actions/workflows/pages.yml)** and select **Run workflow**.
4. Once the deployment succeeds, the URL is **https://SweemingXx.github.io/synth-fab/**.

The automatic workflow token cannot create a Pages site. The one-time setting above is required; never paste a personal access token into the source. Changes whose commit messages contain `[site]` automatically verify and deploy. Manual workflow runs always verify and deploy.

## Experience

- Four scroll-driven production stages and five handoff tabs.
- An original, procedural cyber-organic chameleon, a render-to-texture concept billboard, GPU-morphing point cloud, real triangle/plane section contours, and a textured PEI plate study.
- Adaptive 24,000-point mobile / 72,000-point desktop cloud, with optional 1,000,000-point mode.
- Damped orbit, zoom, reset, keyboard controls, mobile opt-in inspection, reduced-motion support, visibility-based rendering suspension, and CDN/WebGL recovery messages.
- Four material presets, exploded shell inspection, and a gyroid-inspired internal line lattice.
- Cancellable prompt-to-GCode **simulation**, with illustrative receipts and JSON download.
- Three original procedural comparison illustrations and downloadable STL, material-color 3MF, and exact art-direction prompts.
- Accessible dialogs, keyboard focus styling, semantic forms, progress feedback, input validation, and a collaboration brief handoff that previews a public GitHub issue without submitting it.

## Honest boundaries

This is an independent visual portfolio concept. **No real AI services, slicer, printer, or Bambu Connect API are connected.** The gallery artwork is original procedural illustration, not actual generated imagery or photos of manufactured objects. Reconstruction timing and print receipts are fictional demonstrations.

The 3D files are procedurally generated prototype assemblies, **not certified print-ready mechanisms**. STL uses millimeters. The 3MF is a valid OPC ZIP containing a core model and base-material colors; it is not a calibrated Bambu Studio machine preset. Validate geometry, union intersecting shells, check dimensions/clearances/supports, assign compatible materials, and slice before manufacturing. No STEP or real G-code export is provided. The chameleon has an articulated appearance, not validated functional print-in-place joints. PLA/TPU pairings shown in the palette are visual studies, not compatibility recommendations.

## Controls

- Scroll to advance the narrative, or use the five stage buttons.
- Desktop: drag to inspect. Wheel zoom is enabled only during inspection; Escape releases it.
- Touch: tap ⤢ to orbit/pinch, tap again to restore page scrolling.
- Focus canvas: Enter toggles inspection, arrows rotate, +/- zoom, R resets, Escape releases.
- `?` opens contextual help. The pause button stops ambient motion.

## Verification

`tests/browser-smoke.mjs` uses only Node built-ins and the Chrome browser preinstalled on GitHub's Ubuntu runner. The workflow checks JavaScript syntax, WebGL initialization, desktop/mobile overflow, orbit/material state, reconstruction, slicing, all exported binary containers, simulator completion/cancellation, comparison sliders, dialogs, mobile touch scrolling, and reduced-motion behavior. Reports, desktop/mobile screenshots, and sample 3MF exports are retained in the `synth-fab-verification` workflow artifact.

## Design

Space Grotesk / JetBrains Mono. Deep Vibe Void `#0C0E14`, Ghost Chalk `#F3F4F6`, Bambu Racing Green `#00AE42`, Generative Iris `#7C3AED` → `#EC4899`, Electric Amber `#FFB703`, and an additional acid-jade highlight `#BCFF73`. All original geometry and graphics are generated in the page. No third-party photos or paid assets.
