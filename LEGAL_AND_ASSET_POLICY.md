# Legal and Asset Policy

This document records the project's conservative distribution choices. It is not
legal advice and does not guarantee that the project is free of legal risk. Laws and
the analysis of a particular design can vary by jurisdiction and facts.

## Current Choices

- The public-facing project name is `Switch2UI`. The project is independent and is
  not affiliated with or endorsed by any third-party company or product.
- Source defaults use generic sample app labels and empty paths. Names and paths a
  user chooses locally are not project endorsements and should not be committed.
- The controller widget and dock graphics are drawn from generic Rainmeter shapes.
  The prior controller silhouette was replaced with a general gamepad outline.
- Two image files without documented provenance were removed. The dock's news glyph
  is now drawn from simple Rainmeter shapes instead of a bundled image.
- Optional avatars and app images are not shipped. The local `@Resources` folder is
  ignored by Git to reduce accidental inclusion.
- The current working copy may point image variables at local ignored artwork. Clear
  those variable values in any public version; the generic fallback art remains.
- The MIT license is intended for original configuration and source code only. It
  cannot license media, marks, or other rights owned by someone else.

## Non-Negotiable Asset Rules

- Never commit or distribute game covers, box art, character images, logos, product
  icons, screenshots, promotional images, or other copyrighted artwork unless the
  project has clear permission to redistribute each item.
- Do not assume that an image found online, an image used privately, a credit line,
  a noncommercial release, a disclaimer, or a redraw automatically grants permission.
- Do not copy assets from another skin, website, game, app, or device interface.
- For any third-party asset proposed for distribution, retain its source URL, creator,
  exact license or written permission, attribution requirements, and proof that the
  license allows redistribution in a downloadable Rainmeter package. If any detail
  is unclear, do not include the asset.
- User-provided files belong in local `@Resources` and must remain untracked unless
  they have been reviewed and explicitly cleared for redistribution.
- Git ignore rules do not exclude files from a manually assembled Rainmeter package.
  Build from a clean copy, inspect the archive contents, and do not package the
  everyday working folder if it contains personal or unverified media.
- Review fonts, sounds, screenshots, preview images, package metadata, and archive
  contents as well as the visible `.ini` files.

## Naming and Presentation

- Keep unrelated third-party company, product, service, character, and game names
  out of repository defaults, documentation examples, filenames, release titles,
  tags, screenshots, and promotional material. Names of required tools may appear
  only in factual setup instructions.
- Use neutral terms such as `app`, `controller`, `store`, `network`, and `sample`.
- Do not use third-party logos, product marks, distinctive color-and-icon
  combinations, or recognizable interface layouts to suggest affiliation.
- Do not describe the skin as official, endorsed, compatible in an official sense,
  or a recreation of a named product.
- An unofficial-project disclaimer can help avoid confusion but is not a substitute
  for permission and does not cure copyright, trademark, or design concerns.

## Remaining Considerations

- A generic name and original assets reduce specific risks but cannot ensure that a
  highly similar overall layout, trade dress, or visual presentation is acceptable.
  Keep evolving the design toward an independent desktop utility rather than a
  close recreation of a recognizable interface.
- Trademark, copyright, design, publicity, and consumer-protection rules differ by
  jurisdiction. Commercial distribution, monetization, or a takedown notice warrants
  advice from a qualified lawyer familiar with the relevant jurisdictions.
- User-configurable labels and images can still create problems if a public release,
  screenshot, or support post includes unauthorized material. Keep examples neutral.
- Deleting a hosted repository does not erase the local Git history. Removed files
  and old branded configuration values can remain in earlier commits. Before
  publishing a new public repository, start from the reviewed clean tree with fresh
  history, or obtain appropriate advice before rewriting history. Do not push the existing
  history if the goal is to avoid publishing those earlier versions.

## Pre-Release Checklist

- Search tracked files, filenames, documentation, and release metadata for
  third-party brand or game names and remove them from public-facing material.
- Review every image, icon, font, screenshot, and archive entry; verify rights or
  leave it out.
- Check `git status --short --ignored` and `git ls-files` to ensure local assets were
  not staged or tracked.
- Inspect commit history before publishing. A clean working tree alone does not
  remove content from earlier commits.
- Ensure preview screenshots use only generic sample content and contain no private
  user data or unauthorized artwork.
- Keep the README, `spec.md`, license scope, and release contents consistent.
