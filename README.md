# Sif: Field Rover

A class project: a website that explains how artificial intelligence works, told through a farm robot called Field Rover.

## What is on the page
- **Opening:** the rover rolls in under an apple tree, its camera takes a soft photo, it bumps the trunk, and an apple rolls into the page. (Skip button included.)
- **The barn:** the red screen turns out to be a barn door. The camera pulls back to show a red barn, the sliding doors open, and we step into the brown barn interior. A card asks: "Order directly" or "See how everything works".
- **Order page:** "Order directly" keeps you in the barn. The rover slides to the left and an order sheet slides in with the price, chassis color (the rover recolors live), add-ons and Add to cart. Back returns to the choice.
- **Five steps (first on the page):** an isometric farm that walks through one morning (barn, rows, scan, report, farmer). Each step is a big number, a title and one sentence. The facts for each step are pinned onto the scene as small callouts. On phones they become chips under the sentence.
- **Meet the rover:** a daytime farm scene that scrolls past while the rover rolls and its wheels turn.
- **Scan scene:** a point cloud assembles into the rover (how a robot sees), ending on "Meet Field Rover" with a short what-it-is line.
- **The machine:** select a numbered point (or press Auto tour) and the camera zooms to that part while a highlight box frames it. Spin the wheels and read what each part does.
- **Order tab:** a small tab on the right edge of the page. It only says "Order"; the price, chassis color and add-ons show when you press it.
- **Five ideas behind the rover:** input, pattern, prediction, confidence, feedback.

Type: Manrope for headings, Inter for text and labels (both loaded from Google Fonts). Trees are drawn in code (side view in the rover scene, isometric on the farm) with trunks, branches, layered leaves and apples.

## Files
- `index.html` : the whole site (HTML, CSS and JavaScript in one file)
- `assets/` : `rover-nat.png` (rover cutout), `rover-studio.jpg` (the render), `wheel-nat-1.png` and `wheel-nat-2.png` (wheel textures that spin), `chassis-mask.png` (tells the color picker which pixels are body panels)

## Publish on GitHub Pages
1. Create a new public repository, for example `sif-field-rover`.
2. Upload `index.html` and the `assets` folder to the main branch (keep `assets` next to `index.html`).
3. Open Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch", pick `main` and `/ (root)`, and save.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/sif-field-rover/`.

## Notes
- Open it through GitHub Pages (or a local server) rather than by double-clicking `index.html`: browsers block the point-cloud scan and the exact color picker when a page is opened straight from a file.
- The only outside request is Google Fonts (Manrope, Inter). Without internet the page falls back to system fonts.
- Everything on the farm is a concept: the price, the specs and the morning timeline are invented for the project. Nothing is for sale.
- The site respects "reduce motion": the opening, the barn and the moving scenery are turned off, and the page starts on the five-step farm (the Order tab and top Order button still work).
