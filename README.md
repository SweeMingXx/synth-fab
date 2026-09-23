# SYNTH//FAB

**Imagination, materialized.** An interactive generative fabrication portfolio in one `index.html` file.

## Open it

Open `index.html` in a modern WebGL browser, or serve the repository with `python3 -m http.server 8000`. No build step, npm dependencies, API keys, or backend. Internet access is required for Tailwind's CDN, Three.js r128, OrbitControls, and Google Fonts. Essential styling and all artwork are inline.

## Publish once

1. Open **[Settings → Pages](https://github.com/SweeMingXx/synth-fab/settings/pages)**.
2. Under **Build and deployment → Source**, choose **GitHub Actions**.
3. Open **[Actions → Verify and publish SYNTH FAB](https://github.com/SweeMingXx/synth-fab/actions/workflows/pages.yml)** and select **Run workflow**.
4. After successful deployment: **https://SweeMingXx.github.io/synth-fab/**.

The workflow explicitly reports **Site NOT live yet** until Pages is activated. Its automatic token cannot create a Pages site. Do not paste personal access tokens into source code. Once activated, every push to `main` verifies and deploys automatically.

## Experience

- Four scroll-driven stages and five handoff tabs.
- Original procedural chameleon, render-to-texture concept billboard, GPU-morphing point cloud, triangle/plane section contours, and a textured PEI plate study.
- Adaptive 24,000-point mobile / 72,000-point desktop cloud; optional 1,000,000-point mode.
- Damped orbit, zoom, reset, keyboard controls, mobile opt-in inspection, reduced-motion support, visibility-based rendering suspension, and WebGL/CDN error recovery.
- Four material presets, exploded shells, and a gyroid-inspired internal line lattice.
- Cancellable prompt-to-GCode **simulation** with illustrative receipts and JSON downloads.
- Three procedural comparison illustrations; STL, material-color 3MF, and exact art-direction prompt downloads.
- Accessible dialogs, visible focus, form validation, progress feedback, and a collaboration brief that previews a public GitHub issue without submitting it automatically.

## Honest boundaries

This is an independent portfolio concept, not an affiliated product. **No AI services, slicer, printer, or Bambu Connect API are connected.** The gallery contains original procedural illustrations, not AI-generated images or photographs of manufactured objects. Reconstruction timing and print receipts are fictional demonstrations.

The exported models are prototype assemblies, **not certified print-ready products**. STL uses millimeters. The 3MF is an OPC ZIP with geometry and base-material colors, not a calibrated Bambu Studio machine preset. Validate geometry, union intersecting shells, check dimensions/clearances/supports, assign compatible materials, and slice before manufacturing. No STEP or real G-code export is provided. The chameleon has an articulated appearance, not validated print-in-place joints. PLA/TPU palette pairings are visual studies, not compatibility recommendations.

## Controls

- Scroll through the story or use the five handoff buttons.
- Desktop: drag to inspect; wheel zoom activates in inspection mode. Escape releases it.
- Touch: tap ⤢ to orbit/pinch, tap again for normal page scrolling.
- Canvas keyboard: Enter toggles inspection, arrows rotate, +/- zoom, R resets, Escape releases.
- `?` opens contextual help. The pause button stops ambient motion.

## Verification

`tests/browser-smoke.mjs` uses only Node built-ins and Chrome preinstalled on GitHub's Ubuntu runner. It selects a page target explicitly (not Chrome background-extension targets).

The workflow checks inline JavaScript syntax; WebGL/r128 initialization; desktop/mobile horizontal overflow; material/orbit controls; reconstruction and exploded shells; slicing and readouts; build-plate handoff; all STL/3MF binary containers; simulator completion/cancellation; comparison sliders/dialogs; mobile touch scrolling/navigation/help; reduced motion; and uncaught JavaScript errors. Python independently checks all three 3MF ZIP CRCs, XML, vertex references, and material assignments.

Reports, desktop/mobile screenshots, and sample 3MF exports are retained in the **synth-fab-verification** Actions artifact. Verification success does not imply live deployment: check the deployment summary for Pages activation status.

## Design

Space Grotesk / JetBrains Mono. Deep Vibe Void `#0C0E14`, Ghost Chalk `#F3F4F6`, Bambu Racing Green `#00AE42`, Generative Iris `#7C3AED` → `#EC4899`, Electric Amber `#FFB703`, plus acid-jade `#BCFF73`. All artwork and geometry are original and generated in the page. No third-party photos or paid assets.
