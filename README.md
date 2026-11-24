# hmrscience.life

How HMR ties claims to tests: the science bridge (now part of https://universemodel.ai/ui.html) and the East and West page (https://universemodel.ai/east-west.html), condensed.

Static site: `index.html`, `css/style.css`, `js/app.js`, `js/hmr-dock.js`, `favicon.svg`. No build step, no external fonts or CDNs.

- Part of the HMR family of websites: https://hmrfamily.life
- Design picker (bottom left): three looks and a four-level rating, stored in the browser's localStorage. `?design=1` to `?design=3` picks a look.
- `js/hmr-dock.js` is the shared bottom dock (Design, Funsies, React). It is copied from hmrfamily.life and replaced when that file is upgraded.
- Deploy: any static host. `CNAME` is set to `hmrscience.life`.
- Content comes only from pages that already exist on https://universemodel.ai and https://claudebomb.com. Claims are labeled as established science, HMR's view, or open.
- Join us on Discord: https://discord.gg/gEnC8TpNc
