# kiro-atelier-wallpapers — Claude instructions

## What this is
Data-only package: wallpapers painted by Kiro Atelier (KA, private repo `~/KIROTUX/kiro-atelier`), shipped to promote
KA. Installs to `/usr/share/backgrounds/kiro-atelier/`. Package in `nemesis_repo`, recipe
`~/KIRO-PKG-BUILD-APPS/kiro-atelier-wallpapers`, flow `flow-kiro-atelier-wallpapers`.

## Rules — do not break
- Public repo: no hostnames, LAN addresses or private photos in any file.
- Keep KA's file names, including style and strength (Erik, 2026-11-14).
- The current set (2026-11-16, Erik: "grab them from" the pack pool `~/Templates/atelier/`) is 22 different
  pictures in KA's 9 pack styles, sources from public wallpaper sites with unknown artists. `README.md` and
  `usr/share/backgrounds/kiro-atelier/README.txt` say so and offer credit or removal: keep that text. The first set
  (2026-11-14) was one wallhaven picture in 22 styles. Only paid-pack styles exist in the pool, so the premium apps'
  Themes fallback (`ka_wallpaper(style)`) finds no Charcoal Sketch, Linocut … here; harmless while both premium apps
  depend on kirotux-wallpapers, whose paintings come first.
- Picking a set: the pool's per-folder `.kiro-atelier.json` gives each painting's source; skip any source or subject
  used in kirotux-wallpapers or a Ko-fi pack, no brands/logos/text/screenshots/near-photos/real faces, 3840x2160 only;
  check by eye on a contact sheet, then the md5 + 32x18 thumbnail check from HQ `WALLPAPER-PACKS.md`.
- **No doubles across wallpaper packs, ever (Erik, 2026-11-14)**: the free packs and the paid Ko-fi pack never
  share a painting or a source picture. The list of what is where lives in HQ (`Kirotux/WALLPAPER-PACKS.md`,
  offline); check and update it before changing the set.
- Ko-fi link for KA: `https://ko-fi.com/s/6ff5175237` (same as KA Check's `KOFI_URL`).
- JPG only (keeps the package small); after changing the set, rebuild `docs/styles.jpg` (4-wide contact sheet,
  480×270 thumbnails, style and strength burned in).

## Wired elsewhere
- `kiro-variety-config`: `variety.conf` folder source for `/usr/share/backgrounds/kiro-atelier`.
- `kiro-iso` / `kiro-iso-next`: `packages.x86_64`, WALLPAPER block.
