# NotEnoughItems · Zirkumflex QoL patch

Internal NEI build for **GTNH 2.9** (based on `2.8.171-GTNH`). Only your client jar changes; the server keeps stock NEI.

## Install

Copy this prompt into your AI coding agent:

```text
Install the Zirkumflex NEI patch into my GT New Horizons 2.9 Minecraft instance. Do it step by step and stop to ask me if anything is unclear.

1. Make sure Minecraft is not running. If it is, ask me to close it first.
2. Find my GTNH 2.9 instance (Prism Launcher, MultiMC, ATLauncher, CurseForge or the GTNH launcher). It is the folder whose `mods` folder contains `NotEnoughItems-2.8.171-GTNH.jar`. If there are several, ask me which one. If the NEI jar there has a different version, stop and tell me: this patch is only built for 2.8.171.
3. Download the patched jar (public, no login needed) from https://github.com/zirkumflex-group/NotEnoughItems/releases/latest/download/NotEnoughItems-2.8.171-GTNH-zirkumflex.jar into a temp folder.
4. Move (do not delete) the existing `NotEnoughItems-2.8.171-GTNH.jar` out of `mods` into a new `mods-backup` folder next to `mods`.
5. Copy the downloaded jar into `mods`. Check that `mods` now contains exactly one NotEnoughItems jar (NotEnoughEnergistics is a different mod, leave it alone).
6. Tell me the instance path, where the backup is, and how to undo it (swap the two jars back).
```

[**Let me T3 Code that for you →**](https://app.t3.codes/new?prompt=Install%20the%20Zirkumflex%20NEI%20patch%20into%20my%20GT%20New%20Horizons%202.9%20Minecraft%20instance.%20Do%20it%20step%20by%20step%20and%20stop%20to%20ask%20me%20if%20anything%20is%20unclear.%0A%0A1.%20Make%20sure%20Minecraft%20is%20not%20running.%20If%20it%20is%2C%20ask%20me%20to%20close%20it%20first.%0A2.%20Find%20my%20GTNH%202.9%20instance%20%28Prism%20Launcher%2C%20MultiMC%2C%20ATLauncher%2C%20CurseForge%20or%20the%20GTNH%20launcher%29.%20It%20is%20the%20folder%20whose%20%60mods%60%20folder%20contains%20%60NotEnoughItems-2.8.171-GTNH.jar%60.%20If%20there%20are%20several%2C%20ask%20me%20which%20one.%20If%20the%20NEI%20jar%20there%20has%20a%20different%20version%2C%20stop%20and%20tell%20me%3A%20this%20patch%20is%20only%20built%20for%202.8.171.%0A3.%20Download%20the%20patched%20jar%20%28public%2C%20no%20login%20needed%29%20from%20https%3A%2F%2Fgithub.com%2Fzirkumflex-group%2FNotEnoughItems%2Freleases%2Flatest%2Fdownload%2FNotEnoughItems-2.8.171-GTNH-zirkumflex.jar%20into%20a%20temp%20folder.%0A4.%20Move%20%28do%20not%20delete%29%20the%20existing%20%60NotEnoughItems-2.8.171-GTNH.jar%60%20out%20of%20%60mods%60%20into%20a%20new%20%60mods-backup%60%20folder%20next%20to%20%60mods%60.%0A5.%20Copy%20the%20downloaded%20jar%20into%20%60mods%60.%20Check%20that%20%60mods%60%20now%20contains%20exactly%20one%20NotEnoughItems%20jar%20%28NotEnoughEnergistics%20is%20a%20different%20mod%2C%20leave%20it%20alone%29.%0A6.%20Tell%20me%20the%20instance%20path%2C%20where%20the%20backup%20is%2C%20and%20how%20to%20undo%20it%20%28swap%20the%20two%20jars%20back%29.)

## What it changes

1. **Favorites first.** Your favorite (or bookmarked) recipe is shown first on page 1 instead of somewhere on page N.
2. **Favorites that stick.** GregTech tools get a favorite per material, the recipe's output is checked too, and you get a chat note when a saved recipe can't be found.
3. **Bookmarks follow favorites.** R on a bookmark opens your current favorite (crafting-chain bookmarks keep their own recipe).

Uninstall: put the original `NotEnoughItems-2.8.171-GTNH.jar` from `mods-backup` back into `mods`.

---
Fork of [GTNewHorizons/NotEnoughItems](https://github.com/GTNewHorizons/NotEnoughItems), LGPL-3.0. Patches live on branch `zirkumflex/qol`.
