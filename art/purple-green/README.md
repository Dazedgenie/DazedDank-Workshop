# Purple/green Workshop graphics (archived)

An alternative set of Workshop page graphics, saved from the old DazedDank branch
`claude/codebase-init-e66l10` (commit 0d221f5, tag `archive/codebase-init`) before that branch was deleted.
The live Workshop page uses the images in `../../images` and the pipeline in DazedDank `tools/workshop/`.

- `images/`: the rendered PNGs.
- `art/page.html`: the source. Open it in a browser to preview; colours live in its `:root` block.

## Re-rendering

    cd art/purple-green/art
    npm install
    node render.mjs     # needs Playwright: set PLAYWRIGHT_MODULE=/path/to/playwright if it isn't installed here

The sprites in `art/sprites/` were cut from DazedDank's texture packs as they were at that commit.
