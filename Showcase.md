---
tags:
  - stillhaven
  - showcase
status: in-progress
review-date: 2026-10-10
reviewed: false
---

# Stillhaven

A warm workspace for notes, code, and everyday ideas.

Keep the writing simple. Give useful details room to breathe. This sample note
brings a project plan, tables, and a few lines of code into one place.

## Project overview

| Area | Next step | Status |
| --- | --- | --- |
| Research | Collect ideas and useful references | In progress |
| Writing | Turn rough notes into a clear outline | Ready |
| Design | Review the details in light and dark | In review |
| Release | Share the finished work | Planned |

> [!tip] A little room to think
> Start with one clear idea. Add detail when it helps the reader.

## Writing with structure

Use **bold** for decisions, *italics* for a small aside, and `inline code` for
precise names. A [project overview](#project-overview) keeps the next step close.

- A clear title makes a note easy to find.
- Short sections make a long page easier to scan.
- Links connect ideas without repeating them.

### Next actions

- [x] Capture the main idea
- [/] Refine the working draft
- [!] Verify the release details
- [-] Drop the superseded direction
- [ ] Review the finished draft

> A good note makes tomorrow's work easier to begin.

## Code and detail

```javascript
const notes = ["Research", "Writing", "Design"];

function createOutline(title, sections) {
  return {
    title,
    sections: sections.map((name, index) => ({
      name,
      order: index + 1,
      complete: false,
    })),
  };
}

const outline = createOutline("A quieter workspace", notes);
console.log(outline);
```

### More room for tables

| Item | Location | Purpose | Review |
| --- | --- | --- | --- |
| Project notes | `notes/projects/field-guide/` | Keep decisions and next actions together | Weekly <!-- markdown-check: nonbinding-resource --> |
| Reading list | `notes/reference/reading-list.md` | Collect sources with a short explanation of their value | Monthly <!-- markdown-check: nonbinding-resource --> |
| Working drafts | `notes/drafts/a-long-and-descriptive-document-name.md` | Give a longer path and a detailed description enough room | Before sharing <!-- markdown-check: nonbinding-resource --> |

## Embedded context

An excerpt from the Typography section keeps the source close to this plan.

![[Showcase#Typography]]

## Image gallery

In Reading View, a `gallery` callout arranges its images in responsive columns.
Keep descriptions outside the gallery block so its cells contain only images.

> [!gallery] A warm workspace in two modes
> ![Stillhaven appearance settings in dark mode](screenshots/appearance-dark.png)
> ![Stillhaven appearance settings in light mode](screenshots/appearance-light.png)

## Callouts

> [!note] Keep the context
> Record why a decision was made, not just the decision itself.

<!-- Separate callout blocks in CommonMark. -->

> [!warning] Review before sharing
> Replace rough assumptions with checked facts before a note leaves your desk.

<!-- Separate callout blocks in CommonMark. -->

> [!success] Ready for the next step
> A small, complete piece of work is a useful place to continue.

## Typography

### A clear heading

Body text stays readable beside **strong emphasis**, *quiet emphasis*, and
`monospaced details`. The same note can be read in either color mode.

Accents and punctuation belong in everyday notes: café, naïve, résumé,
ľúbivé písmo, číslo 42, and a well-placed em dash — all part of the page.
