# Convert Lessons to McCole Syntax

## Changes Made

### `README.md`
-   Lesson links changed from `./slug/` to `@/slug/` format (required by `mccole` `load_order`)
-   Appendix links changed: `./LICENSE.md` → `@/license/`, `./CODE_OF_CONDUCT.md` → `@/conduct/`, `./CONTRIBUTING.md` → `@/contributing/`, `./bibliography/` → `@/bibliography/`, `./glossary/` → `@/glossary/`, `./advice/` → `@/advice/`
-   Removed trailing link definitions (moved to `_extras/links.md`)

### `_extras/links.md` (new)
-   Created with all link definitions collected from README and all lesson files

### Each `0*/index.md`
-   `[[Key](b:Key)]` → `[%b Key %]`
-   `<cite>Key</cite>` → `[%b Key %]`
-   `<a href="@/slug/">text</a>` and `<a href="../slug/">text</a>` → `[text](@/slug/)`
-   `@/static/files/` → `@/_static/files/` (reflecting user's file move)
-   Per-file link definitions removed (consolidated into `_extras/links.md`)
-   `<div><img ...></div>` blocks → `[% figure slug=... img=... alt=... caption=... %]` shortcodes

### Image shortcode conversions (`07_product`, `08_project`)
| Original alt text | slug |
|---|---|
| DVC | dvc |
| Concept Map | concept-map |
| Timescales | timescales |
| Prioritization (creating) | prioritization-creating |
| Prioritization (using) | prioritization-using |
| Programmer productivity measures from Prechelt | productivity |
