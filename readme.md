# LCARS Enterprise

A Star Trek LCARS ("okudagram") theme pack for the Kiro Crew dashboard.

Transforms the dashboard chrome into the Library Computer Access/Retrieval
System aesthetic: deep-space black canvas, the classic amber `#FF9900`
accent, lilac/periwinkle supporting hues, rounded "elbow" panel corners,
pill-shaped primary buttons, and a framed command-console input line. Ships a
Level-2 computer persona so the assistant answers in the voice of the
Enterprise main computer while the theme is active.

## Palette

Authentic classic LCARS colors (TNG/DS9/VOY era, after Michael Okuda's
designs): orange `#FF9900`, butterscotch `#FFCC66`, lilac `#CC99CC`,
periwinkle `#9999FF`, plum `#664466`, salmon `#CC6666` on black.

- **dark** — true LCARS: black bg, amber text/accent. The intended mode.
- **light** — "daytime ops": a warm parchment canvas keeping the LCARS hues,
  for users who prefer a light dashboard.

## Install

Settings → Display → Install theme, then either:

- **From GitHub** (easiest once published): paste the repo URL
  `https://github.com/flamingquaks/lcars-enterprise`
- **From a local folder**: point at this folder (`lcars-enterprise/`)

Then select **LCARS Enterprise**. Prefer dark mode for the authentic look.

## Notes

- Structural CSS is limited to the surfaces Kiro Crew's theming contract
  allows, so the DOM is restyled, not rebuilt — it reads unmistakably as
  LCARS within those bounds.
- No font is bundled (licensing); the shell uses a condensed sans stack
  (Antonio / Oswald / Saira Condensed) if present, falling back to the system
  font. Install Antonio locally for the closest okudagram letterforms.

## Attribution

LCARS and Star Trek are properties of their respective rights holders. This
is an unofficial fan-made theme, not affiliated with or endorsed by them.
