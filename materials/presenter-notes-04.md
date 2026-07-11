# Presenter notes - Session 4 · Ship it: your page, live on GitHub

Energy note: this is the payoff session. Three weeks of drafting become a public page today. Run it warm and a little ceremonial - the commit-and-refresh reveal deserves a drumroll, the phone-out moment deserves applause. Concepts are deliberately short; protect the lab time.

## Preflight (do these before anyone arrives)

- [ ] **Test account ready.** Have a spare GitHub account with NO username/username repo, so you can create the magic repo live in Demo 1 and everyone sees the "special repository" banner appear for real. Delete last cohort's test repo beforehand.
- [ ] **Your own profile README polished.** Your live profile at github.com/yourusername is the session opener and the proof the trick works. Open it in a tab before class; it is the reveal in Part 0.
- [ ] **Own draft on standby.** Keep a finished about-me page in StackEdit in case someone lost theirs - they can ship a copy of yours as a placeholder and personalize it for homework, rather than sit out the shipping moment.
- [ ] **Tabs pre-opened:** github.com (test account), your live profile, stackedit.io/app with the demo draft, the session page itself.
- [ ] **Backup plan if wifi or GitHub is down:** a recorded walkthrough video (or a full screenshot deck) of Demo 1 + Demo 2 stored locally - repo creation, paste, Preview tab, commit, profile refresh. Narrate over it, have learners ship from home the same evening, and offer a 15-min drop-in call the next day. A gist link to the screenshots also works if only the room wifi is flaky and phones still have data.
- [ ] **Check the GitHub changelog** for any UI changes to the New repository page or the web editor since your last run - button labels move.

## Run of show (45 min)

| Minutes | Beat | Notes |
|---|---|---|
| 0-3 | Welcome + the reveal | Show YOUR live profile first. "This page is markdown you already know. In 40 minutes yours is live too." |
| 3-8 | Part 1: GitHub, no trauma | Repo = folder, commit = save with a note. Promise out loud: no terminal, no git commands today. |
| 8-12 | Part 2: the magic repo | Recite the 4 requirements as a checklist, twice. Have the room say them back. This is the never-forget beat. |
| 12-15 | Part 3 + pipeline SVG | Flavors reality + superpowers map, fast. The SVG frames the lab: "look how short the distance is." |
| 15-23 | Demo 1: create the repo | Everyone creates. Roam the room; the usual snag is the Public radio or a typo'd repo name. |
| 23-35 | Demo 2: THE SHIP | Paste, Preview (Mermaid + badges render here - name the Session 3 payoff), commit "my page, v1", refresh. Phone-out moment at the end. Do not rush this. |
| 35-40 | Demo 3: victory lap | One more commit (v1.1), browse two classmates' profiles, verbal compliments out loud. |
| 40-45 | Show + tell + quiz + close | 2-3 volunteers project their profile. Quiz on the session page. Point to homework + deep-dive track. |

## Never cut these

1. **The 4-requirement checklist recital** (Part 2). Name match, public, README.md in root, has content. It is the debugging tool they take home; say it, have them say it, say it again when someone's profile is blank in the lab.
2. **The commit + refresh reveal** (Demo 2, step 5). Everyone commits, everyone refreshes their profile together. Count it down if you like. This is the moment the course was built toward.
3. **The phone-out moment** (Demo 2, step 6). Phones out, own profile open, show a neighbor. It converts "I did an exercise" into "I shipped something real" - the emotional close of the course.

## Cut if running long (in this order)

1. **Demo 3 victory lap** - compress to just the one extra commit (60 seconds) and move classmate browsing + compliments to homework.
2. **Part 3 editors tour** - it is a self-study card anyway; say "the tools map is on the page" and move on.
3. Show + tell can shrink from 3 volunteers to 1.

Never make up time by shortening Demo 2. Shave anywhere else first.

## Parking lot (likely questions, ready answers)

- **"My username has weird characters - will the repo name work?"** GitHub usernames only allow letters, numbers, and hyphens, so any username is a valid repo name. The trap is exactness, not characters: copy the username from your profile URL and paste it as the repo name. Case doesn't trip the magic, typos do.
- **"Is the repo private by default? Did I just publish by accident?"** The New repository page remembers your last choice, so always look at the radio button rather than assume. And nothing is public until it exists: for the profile README the rule cuts the safe way - if the repo is private, the profile simply shows nothing. You publish only when the repo is public AND you commit content.
- **"Can I undo a commit?"** You can always get back to any earlier version: open the file, click History, open the version you want, copy its content, then edit the current file, paste, and commit again ("back to v1"). Nothing is ever lost; a bad commit costs you one more commit, not your work.
- **"Why is my Mermaid not rendering?"** Fence typo check, in order: the opening fence is exactly three backticks + `mermaid` (lowercase, no space, nothing else on the line), there IS a closing three-backtick fence, and there's a blank line before the block. Also remind them: StackEdit never rendered it - GitHub's Preview tab is where it comes alive, so judge it there.
- **"Can I have more than a README on my profile?"** The profile README is the showcase; pinned repos below it are the next lever - that's their own exploration, point to the awesome-profile-readme homework item.
- **"What if my profile still shows the old content after committing?"** Hard refresh; GitHub caches profile pages for a short time. If it persists, re-run the 4-requirement checklist.

## Close of course

Last slide energy: they arrived four weeks ago never having heard the word markdown; they leave with a live public page, a syntax the whole internet uses, and a publish loop that costs a minute. Say that out loud. Then point at the tweak streak and the deep-dive track so the momentum has somewhere to go.
