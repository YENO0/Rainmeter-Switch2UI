# Switch2UI Project Spec

## Purpose

Maintain an original, generic Rainmeter desktop skin for launching user-selected
applications and displaying basic system information. Keep the project useful as a
downloadable skin without depending on another company's visual identity or media.

## Product Boundaries

- Use generic names, shapes, colors, and interface patterns. Do not describe or
  market the project as an imitation, port, replica, or official companion to any
  third-party product or service.
- Use neutral sample labels such as `Sample App 1`. Users may configure local app
  labels and paths on their own machines; keep unrelated third-party brand and
  content names out of repository defaults, screenshots, examples, release notes,
  and source comments. Names of required tools may appear only in factual setup
  instructions.
- Keep the controller widget generic. Do not recreate distinctive hardware
  silhouettes, logos, button layouts, or product-specific interface arrangements.
- Do not add logos, character art, game covers, screenshots, icons, or other media
  obtained from third parties unless redistribution rights are verified and recorded.
- Prefer original vector-like shapes drawn in Rainmeter configuration. Do not trace
  or closely reproduce a recognizable third-party icon or interface.

## Asset Handling

- `@Resources` is ignored by Git so users can store optional local images there.
- Git ignore rules do not filter a manually assembled package. Build releases from
  a clean copy and inspect the resulting archive.
- Never stage or publish personal avatars, application artwork, covers, logos,
  screenshots, or other media merely because they are present locally.
- Before publishing, inspect tracked files, ignored files, screenshots, archives,
  and the complete Git history. Do not assume `.gitignore` removes files already
  tracked or present in history.
- See `LEGAL_AND_ASSET_POLICY.md` for the asset checklist and residual risks.

## Implementation Notes

- Use `Switch2UI` as the Rainmeter root folder name for installs and packages.
- Skin folders contain their corresponding `.ini` entry points.
- Keep sample app paths empty by default. This local working copy may set image
  variables to files ignored under `@Resources`; clear those values before any
  public commit or release so the generic fallback artwork is used by default.
- Keep project documentation consistent with this spec and the asset policy.
