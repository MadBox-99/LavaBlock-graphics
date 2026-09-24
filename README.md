# LavaBlock Graphics

Sprite sheets and icons for [LavaBlock](https://github.com/MadBox-99/LavaBlock).

This mod declares no prototypes and runs no Lua — Factorio loads it with a
checksum of 0. It exists only so that the pictures are not re-downloaded on
every LavaBlock release: they were 74 MB of a 76 MB mod, so a renumbered
recipe or a corrected line of English cost each player the whole set again.

Install **LavaBlock**, which depends on this. On its own this mod does
nothing.

## Releasing

The two mods are versioned together. A render that changes a sheet is a
release here as well — skipping it leaves players on the old pictures with
no error to warn them, because the path still resolves.

The sheets are built in Blender; the model scripts and the process live in
the LavaBlock repository under `tools/blender/` and `docs/blender-renders.md`.
