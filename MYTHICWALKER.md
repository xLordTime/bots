# MythicWalker bot and block library

Fork of Deimos-Wizard101/bots, GPL-3.0. Original bots remain unchanged.

In **Skripte / Bot**, click **Vom Fork aktualisieren** to refresh all `.txt` files below `bots/`, including your own committed bots. Compatibility is checked before execution; unsupported Expertmode commands are shown explicitly. The full Deimos VM is not included.

Add your own bot below `bots/`. Include metadata `# @name:`, `# @author:`, `# @zone:` (or `*` for any zone), `# @clients:` and `# @format:`. You can also import and save local `.txt` files in the editor.

`default-library.json` is directly importable in the dashboard. `default_lib/` contains standalone block definitions. Edit your own blocks in the dashboard, export/import JSON, and save to the local bridge. Use `call safe_mob_pull` without pasting the definition into your bot. Inline definitions override defaults.

Safe Mob Farm requires hooked clients in a mob zone. Enable the editor Auto-Combat option or fight manually. Each run stops after 15 minutes, and Stop remains available. Loops up to 999999 iterations do not expand the source.
