# Stillhaven — Obsidian Theme

A warmer space for your notes. Stillhaven brings warm charcoal, soft cream,
and muted teal to Obsidian, with embedded typography and thoughtful details
for writing, navigating, and connecting ideas.

![Stillhaven cover with charcoal, cream paper forms, and teal graph accents](screenshot.png)

[![Release](https://img.shields.io/github/v/release/iM3SK/stillhaven-obsidian-theme)](https://github.com/iM3SK/stillhaven-obsidian-theme/releases/latest)
[![Obsidian 1.13.0+](https://img.shields.io/badge/Obsidian-1.13.0%2B-7C3AED)](manifest.json)

[Download the latest release](https://github.com/iM3SK/stillhaven-obsidian-theme/releases/latest)
· [Release notes](CHANGELOG.md)
· [Report a bug](https://github.com/iM3SK/stillhaven-obsidian-theme/issues/new)

## Dark and light

### Warm charcoal

Cream text, a quiet active-file marker, softly tinted callouts, and distinct
task states give longer notes a clear rhythm.

![Stillhaven dark mode showing a callout, headings, outline, and custom task states](screenshots/showcase-dark.png)

### Soft cream

A warm paper palette with teal accents, readable code, and the same note
structure in light mode.

![Stillhaven light mode showing task states, a quotation, and a code block](screenshots/showcase-light.png)

## Ideas, connected

Teal note nodes and clearer connections give Graph view a place in the palette.
Focused notes use a warm highlight; tags and attachments have distinct colors.
Your existing graph color groups remain available.

| Dark graph | Light graph |
| --- | --- |
| ![Stillhaven dark Graph view with teal nodes](screenshots/graph-dark.png) | ![Stillhaven light Graph view with teal nodes](screenshots/graph-light.png) |

## Details for everyday notes

| Detail | What it brings |
| --- | --- |
| Typography | Bundled Geist and Geist Mono, including italic faces; room for prose, code, and tables. |
| Navigation | Built-in folder and file icons, a slim active-file marker, and clear search and command selections. Icons stay hidden while renaming. |
| Structure | A quiet Properties panel, a thin rule under H2, quieter H3 headings, and softly tinted callouts with a slim accent edge. |
| Tasks | Separate symbols for incomplete `[/]`, important `[!]`, and canceled `[-]` items in Reading View and Live Preview. |
| Embedded context | Subtle inset note embeds with their source links and editing controls, plus optional image galleries in Reading View. |
| Controls | Visible keyboard focus and readable destructive confirmation buttons in both color modes. |

## Install manually

Download these four release assets:

- [theme.css](https://github.com/iM3SK/stillhaven-obsidian-theme/releases/latest/download/theme.css)
- [manifest.json](https://github.com/iM3SK/stillhaven-obsidian-theme/releases/latest/download/manifest.json)
- [OFL.txt](https://github.com/iM3SK/stillhaven-obsidian-theme/releases/latest/download/OFL.txt)
- [LICENSE](https://github.com/iM3SK/stillhaven-obsidian-theme/releases/latest/download/LICENSE)

1. Open your vault folder and find its Obsidian configuration folder
   (normally `.obsidian`).
2. Create a `Stillhaven` folder inside `themes`.
3. Copy the downloaded files into that folder.
4. In Obsidian, open **Settings → Appearance** and select **Stillhaven**.
5. Choose the light or dark base color scheme in the same settings page.

The manifest requires Obsidian 1.13.0 or later. No community plugin or separate
font installation is required.

To update a manual installation, replace those files with the assets from the
latest release and reload Obsidian. Stillhaven is not yet listed in Obsidian's
Community Themes directory.

## Sample note

[Showcase.md](Showcase.md) is a synthetic sample note for previewing Properties,
task states, note embeds, image galleries, typography, tables, code, and callouts.
Copy it into your vault together with
[appearance-dark.png](screenshots/appearance-dark.png) and
[appearance-light.png](screenshots/appearance-light.png), keeping both images
inside a `screenshots` folder. Keep the sample's filename so its embedded
Typography section resolves.

## Task states

Write the marker directly in a Markdown task:

```markdown
- [/] Work in progress
- [!] Important detail
- [-] Canceled direction
```

These markers change the appearance in Reading View and Live Preview. Obsidian
treats every non-empty marker as checked; clicking it clears the checkbox. To
choose another custom state, edit the character between the brackets.

## Optional image gallery

Put images inside Stillhaven's custom `gallery` callout:

```markdown
> [!gallery] Reference images
> ![[first-image.png]]
> ![[second-image.png]]
```

Use your own image filenames. Consecutive image lines and images separated by
blank quoted lines both work. Place descriptions before or after the callout;
its content should contain only images. Reading View arranges them into columns
and keeps each image's proportions. Narrow panes use a single column. Live
Preview, Canvas, and print/PDF keep the regular image layout. No plugin is needed.

## Feedback

For layout or styling problems, [open an issue](https://github.com/iM3SK/stillhaven-obsidian-theme/issues/new).
Include the theme and Obsidian versions, your operating system, the light or
dark mode, and steps to reproduce the issue.
If CSS snippets or community plugins are active, check whether the problem also
occurs with them disabled and include that result.

For an improvement suggestion, explain the note-taking task it would help.

## Compatibility and checks

Stillhaven styles Obsidian's existing interface. Built-in controls and editing
behavior remain managed by Obsidian.

The note and graph screenshots above are desktop captures supplied on
10 October 2026. They show the appearance in both color modes; they do not
verify every interaction.

Earlier live checks covered Reading View, Live Preview, command palette,
search, and table scrolling on Windows with Obsidian 1.14.4, before the 1.4.0
additions. Browser fixtures using Obsidian 1.14.4 styles checked callouts,
active-file styling, Properties, task symbols, embeds, headings, and galleries
in dark and light modes, with wide and narrow panes. They also checked checkbox
focus, gallery paragraph breaks, and exclusions for Canvas and print-preview
markup.

The 1.5.0 destructive-button fix was checked in the same kind of fixtures,
including hover and keyboard focus. Graph color classes were checked in
fixtures and their renderer inputs traced in Obsidian 1.14.4.

A complete live review of the 1.4.0 additions and sample note remains pending.
Graph interactions, the minimum declared version, mobile layouts, Canvas, and
Bases have not been separately verified.

## License

Stillhaven's theme code and documentation are licensed under the
[MIT License](LICENSE), copyright (c) 2026 iM3SK.
The bundled Geist and Geist Mono fonts remain under the SIL Open Font License
in [OFL.txt](OFL.txt); the theme's MIT license does not replace their license.

Both complete license notices are also included in `theme.css`, so they travel
with the theme when an installer downloads only the CSS and manifest.

## Project files

- [theme.css](theme.css) contains the styles and embedded font and icon assets.
- [manifest.json](manifest.json) contains the theme name, version, and author.
- [LICENSE](LICENSE) contains the MIT license for the theme code and documentation.
- [OFL.txt](OFL.txt) contains the existing license for the bundled fonts.
- [Showcase.md](Showcase.md) contains the sample note.
- [CHANGELOG.md](CHANGELOG.md) contains release notes.

Created by [iM3SK](https://github.com/iM3SK).
