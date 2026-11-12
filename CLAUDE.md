# Claude Code Instructions — NEXORA Human Atlas

You are working on **NEXORA**, a new, independent 3D human anatomy atlas.

## Product direction
- Build an elegant, modern medical education interface.
- Support Arabic (RTL) and English (LTR).
- Core experience: interactive human body, rotate, zoom, select anatomical systems and organs, and read educational explanations.
- The first release must work as a lightweight static website.
- Keep all previous projects and repositories untouched.

## Technical constraints
- Current implementation: single-page `index.html` using Three.js ES modules from jsDelivr.
- Do not introduce a backend, paid API, paid hosting, or payment integration unless the owner explicitly requests it.
- Do not add secrets or API keys to the repository.
- Prefer accessible controls, responsive layouts, and graceful WebGL fallback messaging.
- Preserve working Arabic and English translations when changing UI.
- Keep performance suitable for mid-range Android phones.

## Medical accuracy and assets
- Treat the current procedural model as an illustrative prototype, not clinical-grade anatomy.
- Do not claim that approximate primitive geometry is medically accurate.
- Before adding any downloaded 3D model, verify its license permits this use and document attribution/license in `ASSETS.md`.
- Use trustworthy medical references for educational copy and add a references section when content is expanded.
- Clearly distinguish educational content from diagnosis or treatment advice.

## Development workflow
1. Inspect the existing files before editing.
2. Make focused changes and preserve the current visual language.
3. Test the page at desktop and mobile sizes; test Arabic RTL and English LTR.
4. Check browser console errors and WebGL loading.
5. Update README with any new setup steps and known limitations.
6. Never delete repository history or unrelated files.
