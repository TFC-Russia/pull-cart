# Changelog

`scripts/release.sh` reads the entry of the version it is releasing from this file and makes it the
release notes, which the Publish workflow then sends on to the mod sites. A version with no entry here
stops the release, on purpose: the note is written before the release, not after it.

Each heading is the mod's own version without the `+<game version>` suffix, so one entry covers both
game lines.

## 1.0.5

- Other mods can reach a chest on the cart through Forge's item handler, the way they reach a chest
  block, while nobody pulls the cart. A cart being pulled keeps its chest to itself.

## 1.0.4

- The mod has its own creative tab, Pull Cart, with the cart, the wheel and the loom. They are in the
  vanilla tabs as well, where they were before.

## 1.0.3

- A jukebox on the cart sends up notes while its disc plays, one a second, the way a jukebox block
  does.
- The mod list links to the mod's CurseForge page and its issue tracker.

## 1.0.2

- The first release on CurseForge. Nothing in the mod itself changed: the cart, the loom and the
  TerraFirmaCraft integration work exactly as in 1.0.1.
- The description shown in the mod list no longer names the server the cart came from.

## 1.0.1

- The cart breaks the way a minecart or boat does. A hit no longer destroys it outright: the damage
  builds up and heals back over the following seconds, and the cart falls apart once it has taken
  enough. One hit still does it in creative, and shift with a hit still takes the loaded block off.
- The cart rocks on its axle while a hit wears off.

## 1.0.0

- The first release: a wooden cart you pull by hand, a wooden wheel, and a wooden loom that spins wool
  into string.
- The cart carries a chest, a crafting table, an ender chest, a furnace that keeps smelting while you
  travel, or a jukebox — or a small animal.
- Loom recipes come from datapacks, so a pack can add its own spindles and spinning recipes.
- With TerraFirmaCraft: TFC item sizes for the cart, the wheel and the loom, a cart loaded with too many
  huge and very heavy items that cannot be pulled, and the cart kept out of TFC's own containers.
