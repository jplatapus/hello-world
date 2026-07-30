# getnoein.com — Design & Positioning Feedback

**Goal:** make the site feel *formidable* — the web presence of a company that is
already running factories, not a startup asking politely for a demo.

**References:** [tenkara.ai](https://tenkara.ai) (direct competitor — AI ops /
supply chain for manufacturers) and [mersenne.com](https://mersenne.com)
(frontier nuclear power, building STARFALL).

> **Caveat:** this environment's network policy blocks direct access to all
> three sites, so I could not do a pixel-level critique of the current pages.
> This feedback is grounded in NOEIN's published positioning and copy (via
> search), what the two references are and how their category presents itself,
> and the audit checklist in §5 — which you can run against the live site in
> five minutes. Re-run this with network access (or screenshots) for a
> screen-by-screen teardown.

---

## 1. What "formidable" actually is

Mersenne and companies like it (Anduril, Base Power, Valar, Hadrian) share a
recognizable grammar. It is not "dark mode." It is:

1. **Declarative copy.** Statements, not promises. "The operating system for
   manufacturing." — full stop. No "revolutionize," no "unlock," no
   exclamation marks. The confidence is in what's *not* said.
2. **Few, enormous words.** One idea per screen. Display type at 80–120px,
   tight leading, generous dead space around it. Whitespace reads as
   confidence; density reads as anxiety.
3. **Engineering-document texture.** Monospace micro-labels (`SYS.01`,
   `READ-ONLY`, `40 kWe`), thin hairline rules, section numbers, spec tables.
   The site borrows the visual language of a datasheet, not a brochure.
4. **A named artifact.** Mersenne doesn't sell "energy solutions" — it builds
   **STARFALL**. A codename makes the thing feel real and inevitable. NOEIN's
   equivalent artifact is the **exception queue / live layer** — name it and
   show it.
5. **Pedigree stated flatly.** "Built companies worth billions. Decades across
   frontier tech, defense, and the national labs." Team credibility as a
   load-bearing section, not an afterthought About page.
6. **Zero SaaS clichés.** No pastel gradients, no floating 3D blobs, no stock
   photos of people pointing at laptops, no "Get started free."

Tenkara contributes the other half — the **proof layer** a serious buyer needs:

7. **Concrete capability, not vibes.** "Agents find, contact, and collect
   quotes from vendors." "Track lead times in real time." Verbs + objects.
8. **A living site.** Features / Why us / About / Blog / Changelog. A
   changelog especially signals shipping velocity. A one-page site signals a
   deck, not a company.
9. **Explicit ICP.** "Built for manufacturers, by manufacturers." The visitor
   knows in one line whether this is for them.

**The play for NOEIN:** Mersenne's gravity + Tenkara's proof. Tenkara reads
competent-SaaS; Mersenne reads inevitable. NOEIN should out-gravity Tenkara
(your direct competitor) while out-proving Mersenne.

---

## 2. What NOEIN already has (use it harder)

From your current copy, you're sitting on excellent raw material:

| Asset | Why it's formidable | Recommendation |
|---|---|---|
| "The operating system for manufacturing" | Category-claiming, declarative | Keep as the hero. Don't dilute with a subtitle full of adjectives. |
| Forward-deployed engineers | Palantir-coded; implies you show up in person | Make it the CTA language: **"Talk to an engineer"**, not "Book a demo". |
| "Live in weeks" over existing ERP | Kills the #1 objection (rip-and-replace fear) | Deserves its own section: a Week 0 → Week 6 deployment timeline. |
| Read-only, isolated tenant, encrypted, every access logged, off the OT network | This is a *security posture*, rare at this stage | Present as a spec block in monospace — it reads like a datasheet and disarms the plant manager and the CISO at once. |
| Exception queue; agents watching planning / procurement / quality | A concrete product artifact | **Show it.** A rendered live console in the hero beats any illustration. |

---

## 3. High-level recommendations

### Layout & structure
Recommended homepage order (mirrored in mockup Direction A):

1. **Hero** — the claim + one sentence + "Talk to an engineer".
2. **The live layer** — a stylized exception-queue console, apparently live
   (ticking clock, statuses). This is your STARFALL.
3. **What the agents watch** — Planning / Procurement / Quality as three
   numbered spec cards. Verbs + objects, no adjectives.
4. **Deployment** — the weeks timeline. Forward-deployed engineers, read-only
   connect, first exception queue stood up.
5. **Security posture** — the spec block.
6. **Company / pedigree** — who builds this, stated flatly.
7. **Final CTA** — one line, one button.

### Typography
- One display face with real presence (Space Grotesk, Söhne, Neue Montreal,
  ABC Diatype — anything geometric and slightly technical). Hero at
  `clamp(3rem, 8vw, 7rem)`, leading ≤ 1.05, tracking slightly negative.
- One monospace (IBM Plex Mono, JetBrains Mono) for labels, data, statuses,
  nav meta. Monospace is doing the "engineering" work of the whole design.
- Uppercase micro-labels with wide tracking (`+0.15em`) for section markers.

### Color
- Near-black ground (`#0A0A0B`), warm off-white text (`#E9E6E0`).
- **One** accent, used sparingly (statuses, the CTA, live indicators). Signal
  orange (`#FF5C1A`) or industrial amber (`#FFB000`) — both read
  "machinery / warning light," which is your world. Avoid the default
  AI-startup purple/blue gradient at all costs — it's the uniform of the
  undifferentiated.
- If you keep a light theme, make it ivory + ink (Direction B), not
  gray-on-white SaaS.

### Motion
- Purposeful only: a ticking UTC clock, a blinking cursor, queue rows that
  update. No parallax, no scroll-jacking, no fade-in-everything. One live
  detail is worth ten animations — it implies the system is running *now*.

### Copy discipline
- Cut every sentence that could appear on a competitor's site unchanged.
- Numbers over adjectives, everywhere. "Connected read-only in 4 days" beats
  "seamless integration" forever.
- CTA hierarchy: primary **"Talk to an engineer"**, secondary "Read the
  deployment brief" (a 2-page PDF/page describing weeks 0–6 — a formidable
  artifact in itself, and great sales collateral).

### Site architecture (steal from Tenkara)
- Add `/security`, `/deployment`, `/company`, and a `/changelog` or field-notes
  blog. Even 3 entries signals a living system. A changelog titled
  "Deployments" (anonymized: "Connected a 3-site metal fab's ERP + supplier
  email, week 2") would be devastatingly effective.

---

## 4. The two mockup directions (in `mockups/`)

| | Direction A — "Command Layer" | Direction B — "Operator Clarity" |
|---|---|---|
| File | `direction-a-command-layer.html` | `direction-b-operator-clarity.html` |
| Mood | Mersenne: dark, cinematic, inevitable | Tenkara-plus: ivory/ink, precise, buyable |
| Bet | Category-defining company | Trustworthy vendor for a conservative buyer |
| Risk | Can feel aloof to a mid-market plant manager | Easier to look interchangeable |

**My recommendation: Direction A.** Your buyer sees Tenkara-style sites weekly;
they do not see Mersenne-style ones from vendors. Direction A also matches the
forward-deployed, "we are the OS" positioning. Direction B is the safe
fallback — or the design system for the docs/product side while marketing
runs A.

All figures, metrics, and quotes in the mockups are **placeholders** —
swap in real numbers before anything ships.

---

## 5. Five-minute audit checklist (run against the live site)

- [ ] Can a visitor state what NOEIN does, for whom, in 5 seconds on the hero alone?
- [ ] Is there exactly one primary CTA above the fold, and is it "Talk to an engineer"-grade?
- [ ] Does any screen show the actual product (queue, console, live view) rather than an illustration?
- [ ] Hero type ≥ 64px on desktop? Line length ≤ 12 words?
- [ ] Count the colors. More than ground + text + one accent → cut.
- [ ] Any sentence a competitor could use verbatim → rewrite or delete.
- [ ] Is the security posture (read-only, isolated tenant, logged, off OT) visible without clicking?
- [ ] Is there any evidence of motion/aliveness (changelog, deployments, live element)?
- [ ] Does the team/pedigree appear anywhere on the homepage?
- [ ] Mobile: does the hero claim survive at 390px width without shrinking to body-text size?
