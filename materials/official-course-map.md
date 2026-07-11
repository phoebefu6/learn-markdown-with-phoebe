# Official course map - learn-markdown-with-phoebe

Course: 4 sessions x 45 min, total beginners, running project = your own GitHub profile page.
Sources fetched and verified: 2026-07-11. Markdown itself is stable; GitHub features (alerts, Mermaid) move - re-verify GitHub changelog before each delivery.

## Source universe

| Source | What it provides | Fetched |
|---|---|---|
| CommonMark 10-min tutorial (commonmark.org/help/tutorial, lessons 01-10 + 99) | Canonical basics sequence + exact syntax rules | 2026-07-11 |
| commonmark.org/help | Quick-reference element set + dingus playground link | 2026-07-11 |
| Daring Fireball markdown project page + basics | History, philosophy, design goal | 2026-07-11 |
| Markdown Guide basic-syntax / extended-syntax / getting-started / cheat-sheet | Full element inventory + best practices + flavor support notes | 2026-07-11 |
| GitHub Docs: basic writing and formatting syntax | GFM beyond CommonMark, exact syntax | 2026-07-11 |
| GitHub Docs: managing your profile README | Exact profile README requirements | 2026-07-11 |
| GitHub Docs: creating diagrams + mermaid.js.org intro/flowchart | Mermaid fence, supported types, minimal examples | 2026-07-11 |

Coverage bar: each session teaches ~80% of its mapped sources' working content live + self-study; the rest lands in self-study accordions or the deep-dive track. Anything not covered is listed honestly at the bottom.

Legend: ✓ = taught live in session · ◐ = self-study accordion on the session page · DD = deep-dive track page

## Session 1 - First words (green)

| Element / fact | Source | Coverage |
|---|---|---|
| What markdown is + why (versatile, portable, future-proof, everywhere) | Markdown Guide getting-started | ✓ |
| History: John Gruber, 2004, v1.0.1 Dec 2004; Aaron Swartz feedback; email-convention roots | Daring Fireball | ✓ (2-min story beat) |
| Design goal: "as readable as possible", publishable as plain text | Daring Fireball | ✓ |
| How it works: .md file -> processor -> HTML; split-pane editor recommended for beginners | Markdown Guide getting-started | ✓ |
| Headings `#`-`######`, space after `#` REQUIRED, blank lines around | CommonMark lesson 04, MD Guide | ✓ |
| Paragraphs = blank-line separated; never indent paragraphs | CommonMark lesson 03, MD Guide | ✓ |
| Line breaks: Enter once does nothing; two trailing spaces or `<br>` (trap!) | CommonMark 03, MD Guide | ✓ |
| Bold `**` / italic `*`, asterisks over underscores mid-word | CommonMark 02, MD Guide | ✓ |
| Bold+italic `***` | MD Guide | ✓ |
| Unordered lists `-` (pick one marker, space after marker required) | CommonMark 06, MD Guide | ✓ |
| Ordered lists `1.` (numerals don't matter, must start at 1, period not paren) | CommonMark 06, MD Guide | ✓ |
| Links `[text](url)` + title; no space between `][` | CommonMark 07, MD Guide | ✓ |
| Escaping `\*` + escapable set | CommonMark 02/06, MD Guide | ◐ |
| Horizontal rules `---` (blank lines around, else setext-heading trap) | MD Guide | ◐ |
| Nested lists: 4-space indent; 8 spaces for code in lists | CommonMark 10, MD Guide | ◐ |
| Setext headings (`=` / `-` underline) | CommonMark 04, MD Guide | ◐ |
| Reference-style links `[text][1]` + `[1]: url` | CommonMark 07, MD Guide | ◐ |
| Autolinks `<https://url>` / `<email>` | CommonMark 07, MD Guide | ◐ |

## Session 2 - Structure (yellow)

| Element / fact | Source | Coverage |
|---|---|---|
| Images `![alt](url "title")`; alt = accessibility | CommonMark 08, MD Guide | ✓ |
| Blockquotes `>`, nesting `>>`, blank lines inside need `>` (trap) | CommonMark 05, MD Guide | ✓ |
| Inline code backticks; double-backtick escape | CommonMark 09, MD Guide | ✓ |
| Fenced code blocks ``` + language id for highlighting (highlighting = renderer-dependent) | CommonMark 09, MD Guide extended | ✓ |
| Tables: pipes + `---` header row (extended syntax, not universal) | MD Guide extended, GitHub Docs | ✓ |
| Table alignment `:---` / `:---:` / `---:` | MD Guide extended | ✓ |
| Task lists `- [ ]` / `- [x]` (GFM) | MD Guide extended, GitHub Docs | ✓ |
| What tables CAN'T hold (headings, lists, images); HTML workarounds | MD Guide extended | ◐ |
| Indented (4-space) code blocks - legacy alternative | CommonMark 09 | ◐ |
| Linked images `[![alt](img)](url)` | MD Guide | ◐ |
| Strikethrough `~~text~~` | MD Guide extended, GitHub Docs | ◐ |
| Task-list `(` escape gotcha `- [ ] \(Optional)` | GitHub Docs | ◐ |

## Session 3 - Polish (orange)

| Element / fact | Source | Coverage |
|---|---|---|
| Emoji shortcodes `:+1:` + autocomplete; copy-paste emoji alternative | GitHub Docs, MD Guide extended | ✓ |
| Collapsed sections `<details><summary>` | GitHub Docs | ✓ |
| Badges via shields.io `![label](https://img.shields.io/badge/...)` - COMMUNITY CONVENTION, not in GitHub docs; attribute to shields.io | community / shields.io | ✓ |
| Mermaid: ```` ```mermaid ```` fence, `graph TD; A-->B;` minimal flowchart (GitHub docs' own example) | GitHub Docs diagrams, mermaid.js.org | ✓ |
| Section links `[text](#heading)` + mini TOC | GitHub Docs | ✓ |
| Footnotes `[^1]` (not in wikis; not in lists/quotes/tables) | MD Guide extended, GitHub Docs | ◐ |
| Alerts: `> [!NOTE]` NOTE/TIP/IMPORTANT/WARNING/CAUTION, no nesting, 1-2 per doc | GitHub Docs | ◐ |
| Sub/superscript `<sub>`/`<sup>`, underline `<ins>` | GitHub Docs | ◐ |
| Light/dark images via `<picture>` | GitHub Docs | ◐ |
| Hidden comments `<!-- -->` | GitHub Docs | ◐ |
| Highlight `==text==` (some processors only) | MD Guide extended | ◐ |
| TRAP: color chips `` `#0969DA` `` render swatches ONLY in issues/PRs/discussions - NOT in READMEs | GitHub Docs | ◐ |
| Heading IDs `{#custom-id}` (processor-dependent) | MD Guide extended | ◐ |
| Mermaid node shapes, directions (TD/LR), link styles, subgraphs | mermaid.js.org flowchart | DD |

## Session 4 - Ship it (red)

| Element / fact | Source | Coverage |
|---|---|---|
| Profile README requirements (ALL 4): repo name = username exactly, public, README.md in root, any content | GitHub Docs profile README | ✓ |
| Creation flow: new repo + "Add a README file" checkbox pre-populates template | GitHub Docs profile README | ✓ |
| Commit via web UI (edit pencil, commit message, commit) | GitHub Docs | ✓ |
| Hiding/removal rules (empty file, private repo, rename mismatch) | GitHub Docs profile README | ✓ |
| Flavors reality: every app implements markdown slightly differently; CommonMark vs GFM split | MD Guide getting-started, CommonMark | ✓ |
| Where markdown lives next: GitHub, Reddit, Slack/Discord, Notion/Obsidian, docs tools, AI prompts | MD Guide getting-started | ✓ |
| Legacy quirk: matching repos created before July 2020 need manual "Share to profile" | GitHub Docs profile README | ◐ |
| Editors tour: StackEdit, Dillinger, iA Writer, Obsidian, VS Code preview | MD Guide getting-started | ◐ |
| Publishing paths: GitHub Pages, Jekyll, Docusaurus, MkDocs (teaser) | MD Guide getting-started | ◐ |
| Mentions `@user`, issue refs `#123` (collab context, brief note) | GitHub Docs | ◐ |

## Deep-dive track (self-paced pages, optional sessions)

| Page | Content | Source basis |
|---|---|---|
| DD1 - Markdown for AI work | Prompts as markdown, CLAUDE.md / agent files, docs-as-context | Phoebe's practice + vendor docs (fetch at build) |
| DD2 - Flavors + export | CommonMark vs GFM vs Extra/MultiMarkdown; pandoc to PDF/docx; static site generators | MD Guide extended intro + getting-started; pandoc docs (fetch at build) |
| DD3 - Mermaid beyond basics | Shapes, directions, sequence/pie/gantt, GitHub version check via `info` block | mermaid.js.org, GitHub Docs diagrams |

## Verified fact box (for slides/pages - do not paraphrase loosely)

1. Markdown created by John Gruber, 2004; final release 1.0.1 dated 17 Dec 2004; BSD-style license; Aaron Swartz credited for syntax feedback (Daring Fireball).
2. Design goal, quoted: make it "as readable as possible" - publishable as-is as plain text (Daring Fireball).
3. CommonMark spec natively includes fenced-code info strings (```` ```python ````), but whether highlighting renders is up to the renderer.
4. GitHub renders 4 diagram fence types: mermaid, geojson, topojson, stl (GitHub Docs).
5. Profile README: 4 requirements above, verbatim from GitHub Docs; no size limit mentioned on that page.
6. Markdown Guide "essential 10" basic set: heading, bold, italic, blockquote, ordered list, unordered list, code, horizontal rule, link, image - our Session 1-2 live set covers all 10.

## Beginner gotcha bank (quiz + callout fuel)

1. Enter once = same paragraph. Blank line = new paragraph. Two trailing spaces = line break (invisible in editors - classic trap).
2. `#Heading` broken, `# Heading` works - space required (also `*item` vs `* item`).
3. Indenting a paragraph 4 spaces accidentally makes a code block.
4. Blank line inside a blockquote breaks it unless the blank line carries `>`.
5. Nested list = 4-space indent; code inside a list item = 8 spaces or a fence.
6. `1)` parenthesis lists and mixed markers = nonstandard; `1.` and one marker type.
7. Literal `*`, `_`, `1.` need backslash escaping.
8. Color chips don't render in READMEs (issues/PRs only).
9. Task list starting with `(` needs `\(`.
10. Emphasis markers must match and hug the text: `*text_` and `* text*` both fail.

## Not covered by design (honest list)

- Definition lists (`: definition`) - rare, low beginner value; named in DD2 flavors page only.
- GeoJSON/TopoJSON/STL diagram fences - named in fact box, not taught.
- Mermaid beyond flowchart basics in live sessions (DD3 exists).
- GitHub certificates/assessments - none exist for markdown; nothing official to defer to.
- R Markdown, MultiMarkdown, Markdown Extra specifics - flavor names only (DD2).
- shields.io full parameter reference - one pattern taught, rest linked out.
- Heading-ID auto-generation rules per platform - section links taught on GitHub behavior only.

## Appendix - fetched syllabi (condensed)

### CommonMark tutorial lesson order (verified 2026-07-11)
01 intro, 02 emphasis, 03 paragraphs, 04 headings, 05 blockquotes, 06 lists, 07 links, 08 images, 09 code, 10 nested lists (file is camelCase `10-nestedLists.html`), 99 end. Playground: spec.commonmark.org/dingus.

### Markdown Guide basic-syntax teaching order
Headings, paragraphs, line breaks, bold, italic, bold+italic, blockquotes, ordered lists, unordered lists, elements-in-lists, inline code, indented code blocks, horizontal rules, links (+ reference style), images, escaping, HTML.

### Markdown Guide extended-syntax element list
Tables (+ alignment, + formatting limits), fenced code blocks, syntax highlighting, footnotes, heading IDs, anchor links, definition lists, strikethrough, task lists, emoji (paste + shortcode), highlight, subscript, superscript, automatic URL linking (+ disabling via backticks).

### GitHub Docs GFM-beyond-CommonMark list
Strikethrough (`~~` or `~`), task lists, tables, emoji shortcodes, mentions/issue refs, 5 alert types, collapsed sections, color chips (issues/PRs only), footnotes (not wikis), sub/sup/ins HTML, `<picture>`, hidden comments, custom anchors, relative + section links.
