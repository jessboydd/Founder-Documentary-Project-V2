# Bear With Me

**The Ready Kit.** *Life happens. Let's figure it out.*

Bear With Me is a beginner-friendly car-preparedness kit: a glove-box organizer, an illustrated guidebook, and a QR-linked mobile site. This design system connects all three so they feel like one product. Its job is in the brief's own words: **make the unfamiliar feel a little more manageable.**

Every rule below is tagged:

- **ESTABLISHED**: already decided in Jess's creative brief or class presentation.
- **NEW**: a recommendation from this system, open for discussion and user testing.

---

## 1. Brand in one breath

Clever, colorful, confident, approachable, playful, educational (ESTABLISHED). The reference point is a lifestyle brand that happens to teach car basics, not an auto-parts store. Joy lives in color, shape and small surprises; credibility lives in clear steps and honest safety copy.

**The rule that resolves most decisions (NEW): Loud outside, calm inside.**
Covers, organizer exteriors, hero screens and section openers get the full lavender/orange/checker treatment. Instruction pages, steps and warnings get quiet surfaces, ink text and generous space. Someone reading on a dark roadside should never have to hunt through decoration.

## 2. Color

| Token | Hex | Role | Status |
|---|---|---|---|
| `lavender` | #B997F8 | Primary brand, hero fields, organizer shell | ESTABLISHED |
| `orange` | #FF7044 | Accent, primary buttons, zipper pull | ESTABLISHED |
| `ink` | #231930 | Headlines, body, icons | ESTABLISHED |
| `ink-muted` | #665D70 | Secondary copy | ESTABLISHED |
| `surface` | #F8F4FC | Backgrounds, paper | ESTABLISHED |
| `surface-tint` | #F0EAF8 | Cards, callouts | ESTABLISHED |
| `line` | #E8E2F0 | Dividers | ESTABLISHED |
| `white` | #FFFFFF | Raised panels | ESTABLISHED |
| `lavender-ink` | #6B44C2 | Links and lavender text on light grounds | NEW |
| `orange-ink` | #B8401A | Orange text on light grounds | NEW |
| `status-stop` / `status-soon` / `status-info` | #C42B3C / #F2B705 / #2E7D4F | Dashboard-light groups | NEW, needs testing |

**Contrast findings (checked against WCAG 2.x):**

- `ink` on `lavender` passes (7.1:1). **White on `lavender` fails** (2.4:1).
- `ink` on `orange` passes (6.1:1). **White on `orange` fails** (2.7:1). So orange buttons carry ink labels. This is also more distinctive than the usual white-on-color button.
- `lavender` and `orange` used as *text* on `surface` fail (2.2:1, 2.5:1). Use `lavender-ink` and `orange-ink` for colored text, or keep the bright colors as fields and shapes.
- `line` is decorative only. Inputs and controls get an `ink` outline.

**Proportion (NEW):** roughly 60% `surface`/`white`, 25% `lavender` family, 10% `ink`, 5% `orange`. Orange should feel like a prize, not wallpaper.

**Safety color rule (ESTABLISHED principle, NEW implementation):** dashboard-light groups are never color-only. Each status pairs a color, a shape and a word:

| Group | Shape | Label | Meaning shown to user |
|---|---|---|---|
| `status-stop` | octagon | STOP SOON | Pull over safely and get help |
| `status-soon` | triangle | CHECK SOON | Get it looked at soon |
| `status-info` | circle | FYI | A system is on; no action needed |

Brand orange is never used for warnings. Otherwise a cheerful accent and a real warning look alike.

## 3. Typography

- **Roboto Condensed** (ESTABLISHED): bold condensed headlines, uppercase for display and labels. This carries the editorial, slightly sporty feel.
- **Body: Figtree** (NEW recommendation): a friendly, open sans available free on Google Fonts. Aptos (ESTABLISHED in the presentation) isn't licensed for web embedding, so Figtree carries body text on the site. Aptos stays fine for Office documents and print drafts. The two are close enough in tone that nothing jars.
- **Mobile sizes (NEW):** body text 17px minimum, step text never below 16px, captions 14px. Line length about 35–45 characters on phones.
- Uppercase only in display and labels; full sentences stay in sentence case for readability.

## 4. Shape, pattern and graphic language

- **Rounded rectangles** echo the organizer and the Kit Bear's head (NEW): `radius-lg` 28px for topic cards and panels, `radius-md` 16px for buttons and step cards, `radius-pill` for chips.
- **Checkerboard** (ESTABLISHED motif, NEW rules): used as a *finish-line* accent, in short strips or corner tiles, never a full background. Checker squares are `ink` + `surface` or `lavender` + `surface`. It marks starts and finishes: cover edges, section openers, the "You did it" screen.
- **Color blocking** (ESTABLISHED): big flat fields of lavender with one orange element. No gradients.
- **Numbered steps** (NEW): big Roboto Condensed numerals in an orange disc with ink numerals. The same component appears in the guidebook and on the site, so the two feel like one product.
- **Icons** (NEW): 2px rounded-stroke line icons in `ink`, on a 24px grid. Dashboard symbols are redrawn simply and always labeled.

## 5. Bear mascot and logo

See **Logo and mascot**. Recommended lead: **Kit Bear**, whose head is the organizer pouch with a zipper smile. It ties the mascot to the product itself. All marks are concepts; none is final (ESTABLISHED: no logo selected yet).

## 6. Illustration

See **Illustration and imagery**. In short: flat shapes, the brand palette, ink outlines only where needed, and simplified car parts. The bear appears as a guide at the edges of pages, never on top of an instruction.

## 7. Voice

ESTABLISHED: a knowledgeable, encouraging friend. Warm, lightly playful, never condescending.

NEW guardrails:

- **Playful headlines, plain instructions.** "Tire looking sad? Let's check it." is fine as a title. The steps beneath use plain verbs: "Remove the valve cap."
- **Safety copy is direct.** No puns, jokes or "no worries" near a red light, smoke, a flat on a highway or a battery. Say what to do and when to call for help.
- **Never promise safety.** Write "If this light is red, stop when it's safe and check your owner's manual or call for help," not "You've got this!"
- **Always point back to the car's own manual** for specs (tire pressure, oil type).

## 8. Accessibility baseline (NEW)

- Text 4.5:1 minimum; large text and icons 3:1.
- Tap targets 48px minimum (`space-7`).
- Information never by color alone.
- Every diagram has a written step beside it.
- Guidebook readable at arm's length in poor light: 10pt body minimum in print, ink on `surface`.

## 9. What still needs deciding

Final logo, organizer dimensions and materials, the category colors for topics (the brief says these need testing), and whether the AI photo-identify feature makes the MVP. Use the Applying the system section for the organizer, guidebook and site.
