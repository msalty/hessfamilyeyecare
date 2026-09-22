# Hess Family Eye Care

Responsive static replacement site. Authored output is in `dist`; regenerate page markup with `python generate.py`. Shared styles and interactions live in `dist/style.css` and `dist/app.js`.

## Content review before public launch

Reviewed https://www.hessfamilyeyecare.com/, /eyewear.html and /directions.html on September 5, 2026.

- Home and directions pages disagree on Middleburg and Mifflinburg hours. This draft uses homepage hours consistently. Confirm with the practice.
- Confirm providers, insurance participation, frame inventory and credit-card surcharge with the practice.
- Appointment links direct patients to location phone numbers. There is no online booking service or collection of patient information.
- Existing URL paths /index.html, /eyewear.html and /directions.html are preserved.
- The published review copy is private. The original domain has not been changed.
- Artwork is illustrative eyewear photography, not a representation of actual products in inventory.

## Implementation

Three standalone HTML pages with shared CSS and a small accessible mobile navigation script. Office hours use native HTML disclosures. Directions use Google Maps search links. No analytics, cookies, third-party fonts or patient-data storage are implemented.

Logo refinement: original eye motif retained, with navy lettering/pupil, deeper green arcs and contemporary sans-serif lettering. Original GIF retained as reference.

Image slideshows: six-second crossfades, navigation, pause/play, keyboard arrows, manual-selection pause, offscreen/background suspension and reduced-motion support. Images are illustrative generated assets, not actual premises or inventory.
