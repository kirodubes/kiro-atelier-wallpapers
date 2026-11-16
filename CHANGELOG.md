# Changelog

## 2026.11.16

### What Changed
- **A new set: 22 different pictures** instead of one mountain lake in 22 styles (Erik: the Look page of the premium
  apps showed 22 near-identical blue lakes in a row). Taken from KA's pack pool (`~/Templates/atelier`), in KA's 9
  pack styles: Dreamscape (6), Palette Knife, Art Deco, Shadow Box, Psychedelic, Layered Paper, Paper Quilling,
  Origami, Monsoon (2 each). Subjects: a snow leopard, a whale, birds, an eagle, a car, space, sea, forest, mountains,
  abstract.
- **No doubles with any pack** (Erik): no painting, source picture or subject from kirotux-wallpapers or the Ko-fi KA
  Wallpapers packs 1 and 2. md5: no copies; the closest 32x18 thumbnails were looked at side by side: other pictures.
- Erik swapped one: the Psychedelic painting from an American-flag photo became a sandy beach with a rock arch
  (Baby Groot, the next candidate, is a Marvel character and was skipped).
- README.md, README.txt and the preview `docs/styles.jpg` describe the new set; the source note covers 22 pictures
  from public wallpaper sites, artists unknown, credit or removal on request.

### Technical Details
- Picked with a seeded script over the pool indexes (source_stem, tag), 3840x2160 only, at most 2-3 per pool folder,
  without women/figures/favorites/text/men/people folders; 11 picks rejected by eye (three logos, Lego, a video-game
  screenshot, made-up text, three near-photos, two nearly empty pictures) and refilled in the same style.
- Copied as KA made them (JPEG quality 92), prefixed `kiro-atelier-` so the premium apps' Themes still find them by
  style; the set is now 26 MB (was 9.3 MB): richer pictures compress less.
- The pack-pool styles have no Charcoal Sketch, Linocut, Edo Landscape, Expressionist, Pastel Light, Morning Wash or
  Default; the premium apps only use this set as a fallback after kirotux-wallpapers (a dependency of both).

### Files Modified
- `usr/share/backgrounds/kiro-atelier/*.jpg` (22 out, 22 in), `usr/share/backgrounds/kiro-atelier/README.txt`
- `README.md`, `CLAUDE.md`, `CHANGELOG.md`, `docs/styles.jpg`

## 2026.11.14

### What Changed
- Initial package: 22 wallpapers painted by Kiro Atelier, one picture in 22 styles, to promote Kiro Atelier on
  the Kiro ISO.
- `README.txt` in the wallpaper folder and a style preview (`docs/styles.jpg`) in the repo.

### Technical Details
- Installs to `/usr/share/backgrounds/kiro-atelier/`; file names keep KA's style and strength.
- Gallery Print converted from PNG (5.6 MB) to JPG; the set is 9.3 MB.
- `kiro-variety-config` gets a folder source for this directory; `kiro-iso` and `kiro-iso-next` list the package.

### Files Modified
- `usr/share/backgrounds/kiro-atelier/*.jpg`, `usr/share/backgrounds/kiro-atelier/README.txt`
- `README.md`, `CHANGELOG.md`, `CLAUDE.md`, `LICENSE`, `docs/styles.jpg`, `up.sh`, `setup.sh`, `kiro.jpg`, `.gitignore`
