# Switch2UI

Switch2UI is an independent Rainmeter desktop skin with a clock, system indicators,
an app carousel, profile placeholders, a generic dock, and a controller-status
widget. The interface uses generic labels and original shapes; it is not an official
interface for any hardware, software, game, or service.

## Install

1. Copy the `Switch2UI` folder into the Rainmeter `Skins` folder.
2. Refresh Rainmeter.
3. Load the individual skins from the `Switch2UI` group.

Use `Switch2UI` as the parent folder name when installing or packaging this project.

## Configure

- In `GameRow/GameRow.ini`, set `App1Name` through `App4Name`, their matching
  `App1Path` through `App4Path` values to local executable paths, and optionally
  `App1Img` through `App4Img` to local image paths.
- In `BottomDock/BottomDock.ini`, set `LauncherPath` to a Rainmeter action such as
  `["C:\Path\To\App.exe"]` if you want to enable the launcher button.
- In `Profile/Profile.ini`, optionally set `AvatarImage` and `AvatarImage2`.
- Keep personal images in the local `@Resources` folder. That folder is ignored by
  Git, but a package made directly from the local folder can still include it.
- Blank local image variables before publishing; the built-in generic art is the
  intended public default.

Only add images or other media to a public package when you created them or have
permission to redistribute them. Build packages from a clean copy and inspect the
archive contents. See `LEGAL_AND_ASSET_POLICY.md` before publishing.

## License

Original configuration and source code are offered under the MIT License in
`LICENSE.md`. That license does not cover third-party material or local files a user
adds to the skin.
