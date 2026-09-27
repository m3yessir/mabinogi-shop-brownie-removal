# m3yessir's Shop Brownie Removal — Mabinogi Mod

**v0.1.0-beta · Mabinogi North America**

Reduces personal-shop clutter by hiding brownie character models, and their overhead names. Shop signs and shop data are left unchanged. This is a standalone file-based .it mod; no DLL injection is used.

## Download and install

Download the release ZIP from this repository's **Releases** section and extract it.

1. Close Mabinogi.
2. Remove any earlier brownie test packages: m3yessirHideShopBrowniesTest_00001.it and m3yessirHideShopBrowniesTest_00002.it. Keep backups outside the package folder.
3. Put **m3yessirShopBrownieRemoval_00001.it** in the active package folder used by your working mods. Common locations are Mabinogi\appdata\package or Mabinogi\package; use the one active for your installation. Keep the filename unchanged.
4. Restart. Check that the shop sign stays visible and opens the item list normally. Also check the brownie label while hovering or holding Alt.

Only the .it file goes in the package folder. To uninstall, close the game, remove that file, and restart.

## What to expect

The author tested Test 2 and confirmed that brownie models and names disappeared while shop signs remained usable. This release contains the same four payload files. This does not establish coverage of every brownie variant or every mod combination.

The same models and races are used by some **housing brownies**, so their bodies and names may disappear too. Clicking an invisible character's body may no longer work. Remove the mod if you need to interact with an affected housing NPC. Names, shadows or separately equipped objects may still appear in some situations. This changes your local display only and makes no FPS-performance claim.

## Compatibility

**Do not use this with Bri Hp Bars (either variant), or another mod replacing data/db/Race.xml or the three model files listed in modified-files.txt.** Whole-file changes do not automatically combine.

The known Erinn Wide View, Sidhe visibility and main-title test packages use different files. File-path checks do not guarantee every mod combination works. This mod is separate from Erinn Wide View.

Race.xml is a snapshot of game data. Check compatibility after game updates, especially when new races or NPCs are added. Remove this mod while investigating new display problems. See [CONFLICTS.md](CONFLICTS.md) for the audited catalog and exact paths.

## Verification

This release has the same four extracted file contents as Test 2. It was repacked under its final filename, then listed and extracted again; all paths, sizes and SHA-256 hashes matched. SHA256SUMS.txt covers the .it file. release-manifest.json records its contents.

Created by **m3yessir**. See [CREDITS.md](CREDITS.md).
