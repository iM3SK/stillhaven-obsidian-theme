# Changelog

User-visible changes are recorded here by release version.

<!-- Keep a Changelog repeats category headings across releases. -->
<!-- markdownlint-disable MD024 -->

## [1.5.1] - 2026-10-10

### Fixed

- Replace the gallery's `display: contents` layout with a compatible Reading View
  layout that keeps images in source order across one to four columns, including
  galleries with blank quoted lines, while retaining regular Canvas and print
  layouts.

## [1.5.0] - 2026-10-10

### Changed

- Give Graph view teal note nodes, a warm focused-node highlight, purple tags,
  orange attachments, quieter unresolved links, and clearer connections.
- Keep native graph interactions and custom color groups intact.

### Fixed

- Make destructive confirmation buttons readable on their tinted red backgrounds
  in both color modes, including hover, while preserving native keyboard focus.

## [1.4.0] - 2026-10-10

### Added

- A quiet Properties panel with clearer labels, values, and native focus states.
- Distinct symbols for incomplete `[/]`, important `[!]`, and canceled `[-]` tasks
  in Reading View and Live Preview, retaining Obsidian's checkbox interaction.
- An optional `gallery` callout for responsive image grids in Reading View,
  preserving image proportions and the regular editor, Canvas, and print layout.

### Changed

- Give note embeds a subtle inset background and edge while retaining their source
  links, scrolling, and Live Preview editing controls.
- Add a thin section rule under H2 and distinguish H3 with quieter color and spacing.
- Expand the sample note with Properties, custom tasks, a note excerpt, and a gallery.

## [1.3.0] - 2026-10-10

### Added

- Give callout cards a soft tint, slim accent edge, and roomier title and body
  spacing while retaining Obsidian's native collapse behavior.
- Mark the active file with a slim teal edge and accented file icon without
  shifting the file list, and hide the marker while renaming.

## [1.2.3] - 2026-10-09

### Fixed

- Include the complete MIT and bundled-font OFL license notices in `theme.css`,
  so they remain available when an installer downloads only the theme files.

## [1.2.2] - 2026-10-09

### Changed

- Make the theme code and documentation available under the MIT license,
  copyright (c) 2026 iM3SK.
- Include the theme's `LICENSE` file as a release asset for manual installation.
- Clarify that the bundled Geist and Geist Mono fonts retain their separate
  SIL Open Font License in `OFL.txt`.

## [1.2.1] - 2026-10-09

### Added

- Warm dark and light palettes with a muted teal accent.
- Embedded Geist and Geist Mono fonts, including italic faces.
- Built-in folder and file icons, wider code blocks and tables, and visible
  keyboard focus.
- A sample note and screenshots for manual setup and previewing the theme.

### Fixed

- Hide folder and file icons while renaming, including files with recognized
  extensions.

<!-- markdownlint-enable MD024 -->

[1.5.1]: https://github.com/iM3SK/stillhaven-obsidian-theme/compare/1.5.0...1.5.1
[1.5.0]: https://github.com/iM3SK/stillhaven-obsidian-theme/compare/1.4.0...1.5.0
[1.4.0]: https://github.com/iM3SK/stillhaven-obsidian-theme/compare/1.3.0...1.4.0
[1.3.0]: https://github.com/iM3SK/stillhaven-obsidian-theme/compare/1.2.3...1.3.0
[1.2.3]: https://github.com/iM3SK/stillhaven-obsidian-theme/compare/1.2.2...1.2.3
[1.2.2]: https://github.com/iM3SK/stillhaven-obsidian-theme/compare/1.2.1...1.2.2
[1.2.1]: https://github.com/iM3SK/stillhaven-obsidian-theme/releases/tag/1.2.1
