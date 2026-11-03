# Drill Pipe International — Mosaic v5

A single-page website for Drill Pipe International, LLC, prepared for a GitHub repository named `drill-pipe-international` and a Vercel project of the same name.

## Deploy

1. Extract all files into the root of the GitHub repository (not inside another folder).
2. Preserve `index.html`, `assets/dpi-logo-v5.svg` and `assets/dpi-mark-v5.svg`.
3. Commit to `main`. The existing connected Vercel project will redeploy automatically.
4. Vercel Framework Preset: **Other**; no package install/build step.

## Updates in v5

- New vector logo derived from the globe and two-line wordmark in the 2026 DPI quotation.
- All visible products/process sequence numbers are single-digit (`1`, `2`, ...).
- Re-selected representative process images with verifiable source captions.
- Three additional photo tiles: machining, inspection/testing, and storage/delivery.
- Added a textured steel-pipe image to the large hero tile without cluttering text.
- Explicit photo disclosures; no claim that any images depict a specific Jindal facility.

## Replace temporary images

Every photograph is an `<img>` inside `index.html` and can be replaced with approved Jindal photographs. Images currently use remote Pexels URLs. See `PHOTO_SOURCES.md` for links and relevant limitations. The new logo is an editable SVG under `assets/`.

## Contact form

This is a static website. The quote form prepares an email in the visitor's email app; it does not send directly from the browser to a server. Add a proper backend later if desired.

## V6 visual update

Six manufacturing-stage photo tiles now use direct source imagery corresponding to the user-selected references, and the land rig is in the Permian Basin rather than offshore. Product tiles feature drill pipe / HWDP rather than generic tubing. Tap **View process detail** to expand process information. See `PHOTO_SOURCES.md` for usage restrictions before publishing.
