# Changelog

All notable changes to this theme are documented here.

## [3.0.2] - 2026-11-08

### Changed
- Display name changed to **Softnight**. The extension ID (`asabhi6776.sniperxjohn`)
  is unchanged, so existing installs update normally.
- Theme file renamed to `themes/Softnight.json`, and the theme's internal name is
  now `Softnight`.
- Separated the warm syntax colours so token types are easier to tell apart:
  parameters are now coral (`#e8a98f`), and types, classes, interfaces and
  namespaces are a lighter yellow (`#ecd88a`). Amber (`#e0a96d`) is kept for
  constants and the UI accent.
- Made errors more visible: all error and invalid colours are now `#ff7b7b`, so they
  no longer blend with the rose used for HTML tags and deleted lines.
- Improved readability with slightly lighter comments, inactive tabs, breadcrumbs,
  line numbers, code lens and status bar text.
- Added subtle depth to the tab area: the active tab is slightly lighter than the
  editor, and tab borders are softer.
- Removed italics from import and flow keywords. Comments, parameters and
  `this`/`self` are still italic.
- Rewrote the Marketplace description, cleaned up the keywords, and lowered the
  minimum supported VS Code version so the theme installs on older releases.

### Added
- Theme colours for UI elements that previously fell back to VS Code defaults:
  inlay hints, sticky scroll, light bulb, quick input and picker groups, command
  center, toolbar hover, code blocks and block quotes, modified-tab border, and
  unnecessary-code opacity.
- Outline and autocomplete icon colours (`symbolIcon.*`) matching the syntax palette.
- `license`, `bugs`, `homepage` and `galleryBanner` fields in `package.json`.

### Note
- The theme label changed from "SniperXJohn" to "Softnight". If your settings
  contain `"workbench.colorTheme": "SniperXJohn"`, select **Softnight** again with
  `Ctrl+K Ctrl+T` (`Cmd+K Cmd+T` on macOS). Any `"[SniperXJohn]"` colour overrides
  in `settings.json` also need to be renamed to `"[Softnight]"`.

## Release Notes for Version 1.2.1

### Major Release Highlights

- *New Eye-Catching Color Scheme:* We've completely revamped the color scheme to provide a more vibrant and engaging coding experience. This release introduces a fresh palette designed to enhance readability and reduce eye strain.

### Changes

- *Drastic Color Combination Changes:*

  - Updated the primary background and foreground colors for better contrast.
Introduced new accent colors to highlight keywords, strings, and functions more effectively.
Modified syntax highlighting to improve visibility and differentiation between code elements.
Improved UI Elements:

  - Updated colors for UI components such as the sidebar, status bar, and activity bar to align with the new theme aesthetics.
Enhanced color differentiation for active and inactive tabs for better navigation.

- *Accessibility Enhancements:*

  - Optimized color contrast ratios to meet accessibility standards, ensuring a better experience for all users.

### Bug Fixes

- *Resolved Color Inconsistencies:* Fixed issues where some text elements were not displaying the intended colors in certain scenarios.
- *Improved Theme Performance:* Optimized color rendering for faster loading times and smoother transitions.
