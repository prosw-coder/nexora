# NEXORA — Human Atlas 3D

An independent, bilingual (Arabic/English) interactive 3D human anatomy learning experience.

## Current preview
- Responsive medical-learning interface.
- Interactive Three.js scene with orbit rotation, zoom, and recenter controls.
- Male/female model selector (currently a UI selection; detailed anatomical differences are not yet modeled).
- System views: full body, skeletal, muscular, circulatory, respiratory, digestive, and nervous.
- Arabic and English interface toggle.
- Educational descriptions for each system.

## Run locally
Open `index.html` through a local static web server. Because the 3D libraries are loaded as ES modules from jsDelivr, avoid opening the file directly with `file://`.

Example:
```bash
python -m http.server 8000
```
Then visit http://localhost:8000.

## Current limitations
This is the first visual prototype. The 3D anatomy is a procedural illustrative model made from Three.js primitives, not a medically validated full anatomical asset. The system buttons switch between illustrative layers. Individual organ selection, labels, detailed male/female anatomy, quizzes, search, and citations to medical references are planned for later development.

## Project rules
- Keep this project independent from all previous NEXORA projects.
- Do not add paid hosting, paid APIs, analytics, or billing without explicit approval.
- Do not present illustrative anatomy as clinically accurate.
- Prefer medically reviewed educational content and appropriately licensed 3D assets.
- Keep Arabic RTL and English LTR fully supported.
