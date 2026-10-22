# Cluelume remote content

Copy the **content/** folder into the root of the GitHub Pages repository that already serves:

`https://lemmidevpixelcraft.github.io/Cluelume/`

So the app expects:

`https://lemmidevpixelcraft.github.io/Cluelume/content/manifest.json`

## Updating words

1. Edit `content/words/de.json` and/or `content/words/en.json`.
2. Keep words at 4–8 normalized letters and use one of the existing categories.
3. Optional `tags` such as `autumn` and `winter` let seasonal events prefer those words.
4. Increase `contentVersion` in `manifest.json`.
5. Commit/push to GitHub. No App Store update is required for content-only additions.

The app always ships with its own full word list and uses the last valid cache if GitHub is unavailable.
