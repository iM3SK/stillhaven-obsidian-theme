# Security policy

## Supported versions

Only the latest release of Stillhaven receives fixes.

## Reporting a vulnerability

Report a vulnerability privately through
[GitHub private vulnerability reporting](https://github.com/iM3SK/stillhaven-obsidian-theme/security/advisories/new).
Do not open a public issue for a security problem.

## Scope

Stillhaven is a CSS theme for Obsidian. It contains no scripts and loads no
remote resources: icons are inline SVG data URIs, and fonts come from the
user's system. A report is in scope when the published `theme.css` or
`manifest.json` could, for example, load a remote resource, hide content from
the user, or misrepresent the interface.
