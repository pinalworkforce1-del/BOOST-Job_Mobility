# BOOST Skill Mobility — Finding Yourself in Work

GitHub-ready static prototype for pilot testing. No server-side components or external libraries are required.

## Test locally
Open `index.html` directly in a modern browser, or run a simple local web server. Audio autoplay is subject to normal browser interaction rules; the interface provides Play/Replay controls throughout.

## Publish with GitHub Pages
1. Create or open the GitHub repository.
2. Upload the contents of this folder to the repository root so `index.html` is at the root.
3. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**.
4. Choose the desired branch (usually `main`) and `/ (root)`.
5. Save and open the Pages URL after deployment completes.

## Prototype behavior
- Participant enters top three O*NET/RIASEC interest codes.
- All six foundational workplace behaviors must be explored before continuing.
- Runtime selects 8 scenarios: 2 from each top-three interest family + 2 outliers.
- First response is preserved as workplace-judgment evidence.
- Corrective feedback does not overwrite the first response.
- Each scenario then presents a Rosie-narrated preference reflection.
- Final output keeps demonstrated evidence separate from preference/development direction.
- Printable results are available through the browser print/PDF flow.

## Canonical map
See `ASSET_CHECKLIST.md` and `asset_manifest.csv`.
