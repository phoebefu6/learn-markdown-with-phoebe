# Presenter notes - Session 2 · Structure: images, quotes, code and tables

45 min live. Audience: total beginners who drafted an about-me page in Session 1.
Goal state at minute 45: every learner's draft has a photo, a blockquote, a skills table, and a task-list checklist.

## Preflight checklist (10 min before doors)

- [ ] stackedit.io/app open in a tab, YOUR Session 1 draft already pasted in (you demo on a real page, not lorem ipsum)
- [ ] Backup editor tab ready: dillinger.io (in case StackEdit is down)
- [ ] Sample image URL tested and loading: your own GitHub avatar `https://github.com/USERNAME.png` - paste it in the address bar and confirm the image renders
- [ ] Second spare image URL in a note, for learners without a GitHub account yet (any stable public image)
- [ ] Course page `02-structure.html` open, "Projector zoom: on" clicked, font legible from the back row
- [ ] Session page quiz answers memorized: 1-B, 2-C, 3-A
- [ ] Quote picked for Demo 1 (short, two lines, so the blank-line-inside-quote gotcha shows naturally)
- [ ] Your 4-6 homework skills listed in a note, ready to type into the Demo 2 table without thinking
- [ ] Timer or phone clock visible to you

## Run of show

| Minutes | Segment | Beat notes |
|---|---|---|
| 0-3 | Welcome + recap | Show YOUR Session 1 draft on screen. "Last week it talked, today it shows." Ask who finished homework skills list; those who didn't invent 4 skills on the spot, no shame. |
| 3-8 | Part 1 · Pictures and quotes | Images = link + bang, alt-text-is-accessibility beat. Blockquote card: land the blank-line-needs-> gotcha verbally, promise they'll see it break in Demo 3. |
| 8-12 | Part 2 · Code | Backtick key location (next to 1) - physically point at it. Fenced blocks: say "highlighting depends on the renderer, GitHub says yes" exactly once, clearly. |
| 12-17 | Part 3 · Tables + checklists | THE framing beat: stop, slow down, "everything until now works everywhere; tables and task lists are GFM - GitHub's dialect - and GitHub is where your page lives." Then pipes, dash row, alignment colons, - [ ] boxes. |
| 17-18 | Part 4 · Roadmap | One breath: milestone 2 of 4 highlighted, "photo, quote, table, checklist - today." Straight into demos. |
| 18-25 | Demo 1 · Photo + quote | Everyone types. Circulate: the two stall points are wrong image URL (page not image file) and missing blank lines around the new ## heading. |
| 25-35 | Demo 2 · Table + checklist | Skeleton first (header + dash row), THEN rows. When someone's table won't render, ask "what's your second row?" out loud - let the room learn the dash-row reflex. End with the checklist and the momentum moment (see never-cut). |
| 35-40 | Demo 3 · Break-it lab | Break all three on YOUR screen, learners follow: quote loses its > blank line, table loses dash row, fence left unclosed. Have the room chant each diagnosis. |
| 40-45 | Q&A + quiz + homework | Run the 3 on-page quiz questions as a group vote. Point at homework: lessons 8-10, three profile READMEs, bring a steal list. |

## Never cut these beats

1. **The blockquote > gotcha demo** (Demo 3, step 1). It is quiz question 1 and the most common wild bug this week. They must SEE the quote split and rejoin.
2. **The tables-are-GFM framing** (Part 3 opening). This one sentence prevents a month of "markdown is broken in app X" confusion. Slow down, say it twice if faces are blank.
3. **The checklist momentum moment** (end of Demo 2): everyone ticks `- [x] Markdown basics` and watches the box render checked. It is the emotional peak of the session - the page now shows PROGRESS. Name it: "you earned that box."

## Cut if running long

- Alignment colons card (Part 3, card 2): compress to one sentence - "colons in the dash row steer columns, it's on your cheat sheet."
- Demo 3, step 3 (unclosed fence): the first two breaks carry the lesson; mention the fence bug verbally instead.
- Nesting quotes (>>) and linked images: already self-study, never demo them live.

## Parking-lot answers

**"Why did my table not render?"**
Ninety percent: the dash row. Row two must be dashes, at least three per column, pipes matching the header. Second suspect: no blank line above the table. Third: the app they pasted into does not support GFM tables at all - which is quiz question 2.

**"Can I use Word instead?"**
Word is a formatting program; markdown is plain text with visible markers. Word's bold lives in the file format and dies in a copy-paste; markdown's `**bold**` survives anywhere text survives, which is why GitHub, Notion, Reddit and every AI chat speak it. Keep drafting in StackEdit - and yes, there are tools that convert markdown to Word when a boss needs a .docx.

**"My image shows a broken icon - why?"**
The URL points at a web PAGE containing the image, not the image file itself. Right-click the picture, "Copy image address", use that. It should end in .png/.jpg/.gif or at least serve a raw image (the GitHub avatar URL does).

**"Do the pipes have to line up?"**
No - ragged pipes render as a perfect grid. Lining them up only helps humans reading the raw file. Do not let perfectionists burn demo time on pipe alignment.

**"Can I put a list or a heading inside a table cell?"**
Not in markdown - cells hold inline things only (bold, links, code). Escape hatch: `<br>` for line breaks inside a cell. If a cell wants a whole list, the content probably wants to be a section, not a table.

**"Why did my checkbox not render?"**
Space matters: `- [ ]` with a space inside the brackets and after the dash. Also task lists are GFM - StackEdit and GitHub render them, some other apps will not.

**"Is the highlighting broken? My python code has no colors."**
Language name goes right after the opening fence, no space: ` ```python `. And highlighting is renderer-dependent - the info string is standard, the colors are the app's choice. GitHub colors ~all common languages.

## After the session

- [ ] Remind: draft is just text - keep the tab open or paste it into any notes app
- [ ] Post the session page link + homework recap in the group channel
- [ ] Note which break-it bug got the most gasps (tune Session 3's lab accordingly)
