# Presenter notes - Session 3: Polish (badges, emoji, collapsibles, diagrams)

45 min live. Learners arrive with their Session 2 draft (photo, quote, skills table, checklist already in).
Energy note: this is the fun session - let the wow moments breathe.

## Preflight (10 min before start)

- [ ] Open `courses/03-polish.html`, projector zoom ON, all cards collapsed.
- [ ] Tab 1: shields.io homepage loaded (it can be slow cold - load it BEFORE class so the badge demo is instant).
- [ ] Tab 2: mermaid.live with an empty editor - backup renderer if GitHub preview stalls during Demo 3.
- [ ] Tab 3: a real GitHub README that shows a badge row AND a rendered Mermaid diagram - your proof-it-works exhibit. Own repo or any well-known repo; verify it renders TODAY (GitHub features move).
- [ ] Tab 4: stackedit.io/app with your own about-me draft from Sessions 1-2, ready to glow up alongside the room.
- [ ] Sanity-check: type `:` in a GitHub comment box once to confirm emoji autocomplete pops (it demos better live than described).
- [ ] Remind the room in chat before start: "bring your draft - today we make it pretty."

## Run of show

| Minutes | Beat | Watch for |
|---|---|---|
| 0-3 | Welcome + where the project stands + win callout | Anyone without a draft: pair them with a neighbor, fix after class |
| 3-8 | Part 1: badges + emoji | Land the honesty beat (below) BEFORE anyone asks "is this markdown?" |
| 8-12 | Part 2: collapsibles + section links | Meta moment: click a course card open - "this page IS details/summary" |
| 12-16 | Part 3: Mermaid fence + shapes/directions | The wow moment - type it live, do not paste (below) |
| 16-18 | Part 4: traps - color chips + alerts + decision-lanes SVG | Zoom the SVG; point at lane 3 |
| 18-25 | Demo 1: badge row (7 min) | %20 for spaces is the stumble; hyphen-in-label needs doubling |
| 25-33 | Demo 2: details + emoji sprinkle + mini TOC (8 min) | Blank line after `</summary>` - the #1 silent failure |
| 33-40 | Demo 3: Mermaid journey diagram (7 min) | No-GitHub-account learners: trust the syntax, verify next week |
| 40-45 | Q&A + homework + REQUIRED GitHub signup reminder | Say "required" twice: no account = no Session 4 publish |

## Never-cut beats

1. **Badges are a community convention.** Say it plainly: shields.io is not markdown and not in GitHub's docs - it is Session 2's image syntax pointed at a badge-drawing service. This honesty builds trust AND reinforces that they already know the underlying syntax. Skipping it leaves learners thinking there is secret badge markdown to memorize.
2. **The color-chip trap.** Swatches render ONLY in issues/PRs/discussions, never in READMEs. Thirty seconds now prevents the most confusing "but it worked in my PR comment" moment on ship day.
3. **The Mermaid wow moment.** Type the fence live, character by character, and let the room watch text become a flowchart. This is the session's emotional peak - if you paste it pre-typed, you refund the wow. Budget the 60 seconds.

## Cuts if running long

- Footnotes card walkthrough (Part 2 self-study) - point at the accordion, say "footnotes live here, they fail in wikis and inside lists/tables," move on.
- Demo 3 branch node - a straight-line 3-node `graph LR` still delivers the wow; the `{decision}` branch can be homework.
- Part 1 emoji dosage riff - one sentence ("seasoning, not soup") carries it.

## Parking-lot answers

**"Why is my emoji code not working in app X?"**
Shortcodes like `:rocket:` are per-app dialect - GitHub and Slack keep their own lists, many apps have none. The character itself (🚀) is universal: paste the real emoji and it works in any markdown app, because it is just text.

**"Do badges slow my page down?"**
Not meaningfully - each badge is a tiny SVG served from shields.io's CDN. The honest caveat: they are an external dependency, so if shields.io is ever down or you are offline, the badge shows as a broken image with its alt text. For a profile page, fine; two or three badges, not twenty.

**"Is Mermaid markdown?"**
No - Mermaid is a separate diagram language with its own project (mermaid.js.org). Markdown's only job is the code fence; the `mermaid` language id tells GitHub to hand the fence contents to the Mermaid engine and display the drawing. That is why it renders on GitHub but not in every markdown editor - stackedit shows the raw text, github.com's preview tab is ground truth.
