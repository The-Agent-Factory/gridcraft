# BRANDING.md: Atelier Sheets (based on GridCraft)

This branch (`academy`) is GridCraft by the ArtCraft team with **rebranding only**, made by
The Agent Factory for Claude Academy. No feature, format or engine code is changed.

| | |
|---|---|
| Upstream | https://github.com/storytold/gridcraft (tag in `UPSTREAM_TAG` of the deploy repo's versions.env) |
| Licence | MIT OR Apache-2.0, unchanged (`LICENSE-MIT`, `LICENSE-APACHE`, `NOTICE`) |
| Name shown in the app | Atelier Sheets (French: Atelier Chiffrier) |
| Credit line | "Based on GridCraft by the ArtCraft team (github.com/storytold/gridcraft)." |
| Not affiliated | with the ArtCraft team, Adobe or Microsoft |

Why: `docs/brand/LICENSE-brand.txt` of the original says a modified version must remove the
ArtCraft name and marks and must not present itself as an ArtCraft product, while plain-text
credit is allowed. The product name GridCraft is not covered by that license; we still
show our own name in the title, About box and start screen so nobody thinks the ArtCraft team
runs this copy. Crate names, binaries and file extensions are unchanged.

Every change is made by `rebrand/rebrand.py gridcraft` in the deploy repo (rules in
`rebrand/apps/gridcraft.toml`); each changed file starts with a one-line change notice.
In-app links: community -> https://www.skool.com/claudeacademy, website -> https://claudeacademy.ca.

## Files changed by `rebrand.py`

- `apps/gridcraft-web/index.html`
- `crates/ui-egui/src/dialogs.rs`
- `crates/ui-egui/src/ribbon.rs`

## Removed (ArtCraft marks, not licensed to forks)

- `docs/brand`
