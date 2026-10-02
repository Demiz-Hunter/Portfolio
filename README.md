# Ross Vieira — portfolio

Single-page portfolio for international recruiters, linked from my CV.
One HTML file, no build step, no framework.

Live: https://demiz-hunter.github.io/portfolio/

## Publish on GitHub Pages

1. Push `index.html` to the `main` branch.
2. On GitHub: Settings → Pages → Build and deployment → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. The site is live at the URL above within a minute or two.

## Keeping it current

- **Photo:** drop a portrait named `ross.jpg` (portrait orientation, about 560×700 px) next to `index.html`. The page shows it automatically; without the file it hides the slot.
- **CV:** drop `cv.pdf` next to `index.html` and uncomment the "Download my CV" link at the end of the Contact section.
- **Text:** everything is plain HTML in `index.html`. Search for `TODO` to find the lines that still need a decision.
- **Footer date:** update "Last updated" when you change the content.

## Design notes

- Type: Archivo (Google Fonts), expanded for display lines, normal width for text.
- Color: cool off-white paper, black ink, one deep-green plane for the results, keypad green only for status and focus.
- Light and dark themes follow the visitor's system setting.
