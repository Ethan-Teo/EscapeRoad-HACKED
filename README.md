# EscapeRoad-HACKED

- `index.html`: Escape Road 3 (embedded from Azgames) with a save tracker and admin panel. Browsers don't let a page reach inside a game loaded from another site, so cheats here only change the page's own tracker.
- `replica/index.html`: **Getaway Arcade**, our own Escape Road-style 3D police chase. The save slots and admin cheats control this game directly: god mode, health, coins, level, wanted level, vehicles and item upgrades all apply live, even mid-run. Coins buy vehicles and item upgrades in the Garage.
- `replica/vendor/three.min.js`: three.js r149 (MIT, see `three.LICENSE`), bundled so the 3D view works offline and on networks that block CDNs. Without WebGL the game falls back to a flat top-down view.

Getaway controls: arrows or A/D steer, ↓ or S brake, Shift nitro, R restart, P pause, M mute. On phones, hold either side to steer, both to brake, and the NITRO button to boost.

Admin panel: 🔒 Admin in the Saves panel (or Ctrl+Shift+A), code `4334`. Save codes from either page import into the other.
