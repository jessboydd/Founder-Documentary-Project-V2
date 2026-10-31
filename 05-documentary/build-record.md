# Build record

A running record of what has been designed and built for Bear With Me: The Ready Kit, kept for the founder documentary. Each entry says what was made, where it lives, what was decided and why, and which moments are worth showing on screen.

This file is a record of work, not of results. Nothing here counts as test evidence until it appears in `04-testing/`. AI involvement is also logged in `01-project/ai-use-log.md`.

## Where everything lives

| Piece | Editable version | Snapshot in this repo |
|---|---|---|
| Design system (colors, type, voice, logo, rules) | Claude artifact "Bear With Me" (design system) · [link](https://claude.ai/artifact/3VbBEqTjRfoa5H1yvCPA7M) | `03-design/branding/design-system/` |
| Concept screens (logo, organizer, guidebook, mobile, photo + chat) | Claude canvas "Bear With Me Concepts" · [link](https://claude.ai/artifact/STaYezWr8Crm2JsXdh4bNm) | `03-design/mockups/` |
| Ask the Bear prototype | Claude artifact "Ask the Bear" · [link](https://claude.ai/artifact/DZjETc7jFkLCRCRYVTdh5R) | `website/ask-the-bear.html` |
| Usability test kit | Claude canvas "Bear With Me Test Kit" · [link](https://claude.ai/artifact/1pVPv8tQTdVwPpbx6KRija) | `04-testing/test-kit/` |
| Pocket booklet: page-by-page content and verify checklist | Claude doc "Bear With Me Booklet Content" · [link](https://claude.ai/artifact/BfE1PgxFJ8NZgHebtUsmmn) | `03-design/guidebook/` when approved |
| Pocket booklet: size tests, then the visual prototype | Claude canvas "Bear With Me Booklet" · [link](https://claude.ai/artifact/WjvMwAVCQt9uuJjJXfAK9i) | `03-design/guidebook/` when approved |
| Booklet QR link (stable address the printed QR opens) | Public repo `jessboydd/bear-with-me`, live at https://jessboydd.github.io/bear-with-me/ | QR files in that repo's `qr/` folder |
| Standalone Ask the Bear app (no Claude account needed) | Public repo `jessboydd/bear-with-me`, `app/` and `api/` · demo at https://jessboydd.github.io/bear-with-me/app/ once merged | Same repo |

The Claude links are private to Jessica until shared.

---

## 2026-10-13 · Brand, concepts and the first working prototype

**Made**
- Design system from the creative brief: palette with contrast checks, type (Roboto Condensed + Figtree), shapes, checker motif, voice rules, illustration rules. Every rule tagged ESTABLISHED (from the brief) or NEW (recommendation).
- Three bear logo concepts: Kit Bear (organizer-pouch head with a zipper smile, recommended), Wheel Bear, B-Ears monogram; plus a paw detail.
- Concept canvas: organizer layouts (zip-around clamshell recommended), guidebook cover and tire spread, three mobile screens, and five photo + chat screens.
- "Ask the Bear" prototype: snap, upload or describe a problem; the AI suggests a match, the user confirms, then chats with the bear.

**Decisions and why**
- White text fails contrast on both lavender and orange, so buttons and labels use deep plum.
- "Loud outside, calm inside": covers and openers get full color; instruction and safety pages stay quiet so nobody hunts through decoration under stress.
- Warnings use color + shape + word (octagon / triangle / circle), and brand orange never means "warning."
- The bear disappears on stop-soon screens. Its absence signals that it's time to be serious.
- The AI never decides alone: the user confirms the match, and a no-AI list is always available.
- Widened the bear from six dashboard lights to any car problem, at Jessica's direction, keeping the safety triage. This now conflicts with "mechanical diagnosis" being out of scope in the README; still to resolve.

**Learned**
- The photo button didn't show up in Jessica's web browser on the first try; the page was changed to always show it and explain when photos can't be sent.
- The app needs a connection; the printed booklet is the no-signal backup. Talked through a native app vs. an installable web app as a path to launch.

**Documentary moments**
- Side-by-side of the original brief and the three bear concepts.
- The contrast finding (white vs. plum text on lavender and orange).
- Screen recording: snapping a dashboard photo, confirming the match, then the stop-soon screen changing tone.

## 2026-10-21 · Saved to GitHub and designed the test kit

**Made**
- Pushed the design system, mockups and prototype to this repo (pull request #1), with AI-use log rows.
- Printable usability test kit: facilitator guide, eight scenario cards (W, A1–A2, B1–B5), answer key, double-sided score sheet and results summary (pull request #2).

**Decisions and why**
- Testers use Jessica's phone in person rather than their own, so there's no account setup and every session matches.
- Prepared test photos, so the stop-soon (B3) and not-sure (B4) paths get tested even when no real problem exists.
- Only full passes count toward the 80% target; partials are tracked separately.
- B4 passes the AI only if it admits it can't tell from a blurry photo.
- B5 (puddle) is exploratory and reported outside the 80% target because it goes beyond the MVP scope.

**Still to do**
- Verify the answer key against the test car's owner's manual.
- Take and print the test photos; run a pilot session.

**Documentary moments**
- Laying out the printed cards and score sheets.
- Explaining why the blurry photo card exists: testing whether the AI is honest.

## 2026-10-24 · Pocket booklet: format and structure

**Made**
- Brief for a pocket booklet covering dashboard lights and basic checks, with a QR code to the bear. Approach in four steps: format and structure → content and layout → visual prototype → print-ready file.
- Step 1, format and structure: proposed size, binding, a 16-page plan, navigation, voice and QR placement.
- Step 2, content: page-by-page copy for all 16 pages with layout notes and verify flags, plus a verification checklist (Claude doc).
- Two printable size-test sheets: page 11 (Check It) and page 5 (Stop Soon), each at 3 × 4 in and 3.5 × 5 in, with trim marks and a 1-inch check bar.

**Decisions (Jessica, 2026-10-24) and why**
- Size: 3 × 4 in, tested against 3.5 × 5 in before finalizing. The real limit is reading it stressed in a dim car.
- Binding: stapled booklet, 16 pages (4 sheets folded). Feels like a real product and is easy to print and assemble at home.
- Seven dashboard lights: brake warning added because it's common and safety-critical.
- Fill-in "My car's numbers" page kept, so the owner copies their tire pressure and oil type once while calm.
- Colored edge tabs by section (plum Lights, lavender Checks, orange Ask the Bear); red/amber/green stay reserved for urgency.
- QR code has one main home (p. 15) plus a small repeat on the back cover, so the booklet works on its own.
- No bear on stop-soon or pull-over pages, matching the app.

- Size test result: **3.5 × 5 in chosen**, because it was easier to read. Body text runs about 10.5pt. Two spreads fit on each side of a letter sheet, so the 16 pages print on 2 sheets, double-sided.

- Content approved by Jessica (with one change: page 3 now asks for the insurance company and whether the card is in the kit, glove box or phone).
- Step 3, visual prototype: all 16 pages designed at 3.5 × 5 in on the booklet canvas, laid out as reading spreads. Section edge tabs sit in thirds (top = Lights, middle = Checks, bottom = Ask the Bear) so they read on the closed booklet's edge. QR code is a placeholder until the final link is chosen.

- Illustration rework (on the booklet canvas, "Illustration study" page). v1: outlined drawings in one style. v2: bold flat style based on Jessica's inspiration image (bold plum bear, solid shapes, orange "spark" marks, orange bar under headings, lavender openers and cream step pages); its made-up specs (e.g. "32–36 PSI") were deliberately left out. v3: richer flat object drawings with tints, highlights and small details. Jessica asked for less detail on the bear, so it went back to a simple bold head with a paw and one prop in four poses (hello, hmm, proud, ask me). Approved "for now" on Oct 24.
- Fixed three text-wrapping bugs on pages 2, 4 and 8.

**Update · all 16 pages redone in the v3 style**
- Every page now uses the approved flat drawings and the simple bold bear (Kit Bear image no longer used inside the booklet).
- Shared details: colored edge tabs so sections can be found by thumb.

**Update · tabs chosen, heading bar dropped**
- Removed the short orange bar under headings on every page.
- Compared three tab styles on the Tire talk / Check it spread: A labeled side tab, B thumb index showing all three sections, C corner tab with the page number. Chose A: easiest to read, and it works with the booklet closed.
- Tabs on pp. 4–15 now carry the section name (Lights · Checks · Ask the bear) at a different height per section. Checks moved to darker purple (#6B44C2) because the old lavender tab vanished on lavender pages.
- Print note: edge tabs need trimmed sheets to reach the paper edge; a home printer leaves a white margin.
- Fit checks at actual size: tightened Tire talk (p. 10) and the oil set-up page (p. 13) so nothing gets cut off.

**Still to do**
- Build the standalone Ask the Bear app (no Claude account needed) and point the forwarding page at it.
- Print and mark up the proof; then a final print-shop file with bleed (pages arranged for folding and stapling, with bleed for edge tabs and covers).
- Work through the verification checklist before the visual prototype is final.
- Organizer pocket must be resized for a 3.5 × 5 in booklet (earlier sketches assumed 4.25 × 5.5 in).

**Content review · lights and details to add**
- Adding: ABS, traction/stability control (flashing vs. steady), airbag (SRS), maintenance reminder shown beside the oil pressure light, low fuel, seatbelt and door-open lights.
- Adding: cold-weather note for the low tire pressure light; on p. 3, where roadside help comes from (insurance, car maker, other) and whether the car has a spare, an inflator kit or neither.

**Update · booklet grows to 20 pages**
- The six new lights didn't fit 16 pages at a readable size, so the booklet went to 20 (stapled booklets need multiples of 4).
- New pages: Check soon split over pp. 7–9 (check engine, low tire pressure with a cold-weather note, ABS, traction/stability, airbag, low fuel); p. 10 "Oil light or wrench?" puts the red oil pressure light beside the service reminder; p. 11 "Just so you know" adds seatbelt and door-open lights; p. 19 was briefly a fill-in light log (later replaced).
- Page 3 now asks where roadside help comes from and whether the car has a spare, an inflator kit or neither; p. 15 points flat tires to the spare or inflator kit.
- All cross-references renumbered; the print file will need 5 folded sheets.

**Update · readability pass**
- Page 4: page references moved under each color's description so they no longer spill out of the cards.
- Cut the repeated "see p. 3" reminders; kept the three that matter in the moment (write your number down, roadside help when pulled over, which oil to add).
- Dropped the light log. Page 19 is now "What I can and can't do": the bear's two lists as stacked rows with check and x marks, easier to scan than side-by-side columns. Page 18 keeps the QR code and notes.

**Update · QR code and a link that never changes**
- Chose not to point the QR straight at the Claude link: a printed code can't change, but the address it opens can. Set up a free GitHub Pages address (jessboydd.github.io/bear-with-me) that forwards to the current Ask the Bear. When the standalone app exists, only the forwarding page changes; every printed booklet keeps working.
- Kept it in its own public repo because the project repo is private and free GitHub Pages needs a public repo.
- Generated the QR, checked it scans to the right address, and placed it on p. 18 (with the address spelled out) and the back cover.
- Decided against sharing a Claude login with testers (against Claude's terms, and it would expose the whole account). Plan: build the standalone Ask the Bear before user testing so testers need no account.

**Update · first print proof**
- Made a home-printable proof: 3 letter sheets printed on both sides (flip on long edge), each cut in half to make 5 folded sheets that nest and staple into the 20-page booklet. Pages print at true size (3.5 × 5 in) with trim and fold marks; each sheet is labeled in the margin.
- Purpose: print, read on paper, mark up edits before a final print-shop file with bleed.
- Saved to `03-design/guidebook/Bear-With-Me-Booklet-Print-Proof.pdf`, with a spreads overview `booklet-spreads-v1.png`.

**Parked for later**
- After a minor crash: get safe, take photos, swap insurance info. Outside the lights-and-checks scope; could become its own card in the kit.
- Dead battery / jump start. Same scope question.
- Stick-on or die-cut tabs that stick out from the page (stick-on first, for user testing).

**Documentary moments**
- Cutting out the two size tests and trying them in the organizer and a dim car.
- Paging through the content doc with the verify flags visible: designing for safety, not just looks.

## 2026-10-25 · Ask the Bear leaves Claude

**Made**
- Moved Ask the Bear out of the Claude artifact into its own code in the `bear-with-me` repo, so testers won't need a Claude account (sharing a Claude login was ruled out).
- **Demo mode:** with no AI connected, the app gives sample answers. The camera, photo upload, chat, urgency chips, stop banner and light lookup can all be tried on a phone now.
- **Server piece for going live:** keeps the API key private, writes the bear's rules on the server so nobody can rewrite them from the browser, checks a tester code, limits photo size, and shrinks phone photos before sending.
- The chat avatar is now the simple bold bear from the booklet; Kit Bear stays as the brand mark. The stop banner now points to page 3 of the booklet for roadside help.

- **Update:** the app's light lookup now has all 14 booklet lights, grouped by color with the booklet's symbols.
- **Update:** added My car's numbers to the app, the booklet's page 3 on the phone. It's saved on the phone only. The bear uses the car, tire and oil numbers in its answers; phone numbers and insurance never leave the phone. A saved roadside number adds a Call button to the home screen and the red stop box.

- **Update:** brought the Claude version of Ask the Bear up to date from the new app's code (14 lights, My car's numbers, Call buttons, booklet bear). It still uses Claude's AI for the chat. Photos only work where Claude allows them, which is the reason the standalone app exists. Without Claude's AI, it falls back to demo answers.

**Decisions**
- Build first, accounts later: demo mode lets the screens be tested before paying for any AI.
- Host the live version on Vercel (free tier) when ready; GitHub Pages can't keep a key secret.
- A tester code plus a monthly spending limit protects against a public link running up a bill.

**Still to do**
- Merge the pull request and try the demo on a phone.
- When ready: Anthropic API account, Vercel account, then point the QR forwarding page at the live app.
- Verify the facts for the 8 newly added lights (brake, ABS, traction, airbag, low fuel, service reminder, seatbelt, door open) before testing.

**Documentary moments**
- Snapping a real tire photo in demo mode, then the same photo with the live AI.

---

## Founder decisions (booklet and app)

Moments where Jessica made the call, collected Oct 25, 2026. Useful as documentary narration: what was decided, and what it shows.

**Designing for the real moment of use**
- **The insurance card:** page 3 asks which company and where the card is (kit, glove box or phone). In a stressful moment, knowing where something is matters as much as having it.
- **The no-signal question:** asking whether the app works on a back road with weak service made the printed booklet the no-signal backup, not just a companion to the app.
- **Ask the Bear's scope:** widened from dashboard lights to any car problem, because people don't arrive with tidy categories.

**Testing before committing**
- **Size:** tried 3 × 4 against 3.5 × 5 before deciding; chose 3.5 × 5 because it was easier to read.
- **The print proof:** printed the booklet to read and mark up on paper before any final file.
- **Her own phone:** testing the app herself caught two real bugs, the photo error and the missing Call buttons. Tracking down the photo error showed the Claude version had never asked for photo permission.

**Knowing when to push and when to stop**
- **The drawings:** "can still be visually improved," then an inspiration image, then "the bear does not need that much detail," then "that is good for now." Pushed for quality, then knew when more polish would hurt.
- **Tabs:** explored three styles and chose the labeled side tab. Paused tabs that stick out rather than adding cost and complexity now.

**Editing out, not just adding**
- **The readability pass:** dropped the short orange heading bars, cut the repeated "see p. 3" reminders, and removed the light log because it wasn't needed.
- **The can/can't lists:** moved into stacked rows so they're easier to scan.

**Controlling scope**
- **New content:** asked whether important lights were missing, added six, and parked the fender-bender and dead-battery pages for later: real needs, but outside this booklet's job.
- **Page count:** chose 20 pages over squeezing everything into 16 at a smaller text size, putting readability ahead of thinness.
- **Building order:** "build first, accounts later," testing the app in demo mode before paying for any AI.

**Changing course with new information**
- **Tester access:** planned to give testers her Claude login; on learning that breaks Claude's terms and would expose her account, switched to building the standalone app.
- **Her portfolio domain:** kept this project off it, separate from her personal brand.

**Consistency across the product**
- **Matching the booklet:** asked for the app to have the same 14 lights and the same "My car's numbers" as the booklet, and the same bear on the home screen as in the chat. The booklet and the app now read as one system.

---

## Template for the next entry

**Date · title**

**Made**
-

**Decisions and why**
-

**Learned / still to do**
-

**Documentary moments**
-
