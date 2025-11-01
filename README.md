# RemoveNitroNameCustomization

Revert user displaynames to not show custom fonts or colorations that nitro permits.

Tested against a few, but not all, effects introduced around mid October 2025 patch. Also tested against other themes, no conflicts generally found unless those themes also played around with the attributes that this project's .css file works with.

What this patches:
- Displayname fonts : reverts them back to the default app font
- Displayname coloring : reverts them back to whatever your current theme uses, or otherwise just the default app text color
- Displayname effects : reverts extra visuals on text, ie strokes, glow/neon, animation changes.

What this doesn't do:
- Does not remove/patch-out profile effects, nameplates, or other visuals that don't mess with the displayname.
- Does not touch guild tags. They are left alone.
- Does not solve the meaning to life, but I hear 42 is a sound one.
