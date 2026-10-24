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
- Step 4: print-ready file (pages arranged for folding and stapling, with bleed for edge tabs and covers).
- Work through the verification checklist before the visual prototype is final.
- Organizer pocket must be resized for a 3.5 × 5 in booklet (earlier sketches assumed 4.25 × 5.5 in).

**Content review · lights and details to add**
- Adding: ABS, traction/stability control (flashing vs. steady), airbag (SRS), maintenance reminder shown beside the oil pressure light, low fuel, seatbelt and door-open lights.
- Adding: cold-weather note for the low tire pressure light; on p. 3, where roadside help comes from (insurance, car maker, other) and whether the car has a spare, an inflator kit or neither.

**Update · booklet grows to 20 pages**
- The six new lights didn't fit 16 pages at a readable size, so the booklet went to 20 (stapled booklets need multiples of 4).
- New pages: Check soon split over pp. 7–9 (check engine, low tire pressure with a cold-weather note, ABS, traction/stability, airbag, low fuel); p. 10 "Oil light or wrench?" puts the red oil pressure light beside the service reminder; p. 11 "Just so you know" adds seatbelt and door-open lights; p. 19 is a fill-in light log (date, light, what I did).
- Page 3 now asks where roadside help comes from and whether the car has a spare, an inflator kit or neither; p. 15 points flat tires to the spare or inflator kit.
- All cross-references renumbered; the print file will need 5 folded sheets.

**Parked for later**
- After a minor crash: get safe, take photos, swap insurance info. Outside the lights-and-checks scope; could become its own card in the kit.
- Dead battery / jump start. Same scope question.
- Stick-on or die-cut tabs that stick out from the page (stick-on first, for user testing).

**Documentary moments**
- Cutting out the two size tests and trying them in the organizer and a dim car.
- Paging through the content doc with the verify flags visible: designing for safety, not just looks.

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
