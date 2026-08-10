# NOEIN — Customer Discovery Evidence Brief

**Period covered:** April – August 10, 2026
**Sources:** 106 logged meetings (Granola call notes, May 1 – Aug 10), NOEIN Contact Management CRM (Airtable, 64 organizations), customer email threads (Gmail)

---

## Headline numbers

| Metric | Value | Source |
|---|---|---|
| Meetings logged in the last 14 weeks | 106 | Granola, May 1 – Aug 10 |
| Customer conversations (calls + summit meetings) | 35+ | Granola + CRM |
| Manufacturers & industrial companies engaged | 30+ | Airtable CRM (64 total orgs incl. investors/vendors) |
| Paid pilots | 3 (2 deployed, 1 signing as of Aug 4) | Dynamo call notes, Aug 4 |
| Near-term ARR from pilot expansion | ~$500K | AVESTA call, Jul 17 |
| Qualified pipeline | ~$1.5M | AVESTA call, Jul 17 |
| Countries with active customers | 3 (Poland, Canada, US) | Mitsubishi call, Jul 16 |

---

## 1. Who we talked to

**Signed / deployed pilots**
- **ILUM** (Poland, architectural lighting; 5,500 m² factory, #1 petrol-station lighting in Poland, KFC's #1 lighting vendor in Europe) — 7 calls May 27 → Jul 28. BOM automation pilot signed at $7,500; expansion path ~$100K/yr.
- **Mago Group / POSM Factory / PerfectData** (Poland; $150–200M group revenue, 1,200+ employees, 4 plants, 30,000 store shelves/day) — 6+ calls May 12 → Jul 27. Invoice-to-project matching pilot (KSeF/Enova).
- **Roll Froz** (Poland, frozen food; search-fund acquisition Sept 2025) — 2 calls Jul 14 & Jul 22. ~€15K indicative pilot; quote-to-capacity agent scoped. **Referred by an existing pilot champion.**

**Active scoping**
- **Conestoga Meats** (Canada, pork co-op owned by ~160 farmers) — 3+ calls + email thread May → Jul. 60-day document-controls pilot going through their PMO approval (July 8 managers session).
- **Mitsubishi Electric** (Japan/US, via Plug and Play) — factory-automation group; zero-integration sample dashboard proposed as entry.
- **MARS Supply** (US, industrial distribution, est. 1924, ~$12M JIT inventory) — referral source; named Toro, 3M, Kurt Manufacturing; offered intros to Enterprise Minnesota and the Minnesota Precision Manufacturing Association (~200 shops).

**Corporate / summit pipeline (PnP Silicon Valley May Summit and after):** FUJI Corporation, Ecolab, TREMEC, Granite Construction, Infineon, Doosan Bobcat, Panasonic, Toyota Boshoku, Calmax, EnerSys, Sakuu, Orlen, L3 Harris, and others (CRM).

**Discovery / adjacent-market probes:** Amber Bauxite & Alumina (50K-document archive copilot), Frank (mining archives), i3 (mining equipment risk), MeshNex (EU mid-market digitalization), 450 Alliance.

---

## 2. Top learnings (each backed by a customer data point)

### L1. The pain is cross-system reconciliation, and customers can quantify it
- ILUM: BOM creation takes **2–3 weeks per order**; **80% of components are identical across orders**; 4 constructors fully booked doing repeat documentation. Inventory: system says 200 pieces, shelf quantity unknown; production stops over untracked screws.
- Mago/POSM: every incoming invoice requires the CFO to run **15–30 email threads** to find who ordered it and for which project; Poland's KSeF system dumps all supplier invoices into one central mailbox.
- Conestoga: capital-project cost tracking is fully manual Excel; quote from the Engineering Manager: *"Crazy in 2026 it's not me just clicking a button."*
- Roll Froz: using **~20% of its ERP's capability**; stock levels on paper; three disconnected process steps with no data flow between them.

### L2. "We have no data / we're not ready for AI" dissolves on contact
FUJI's initial objection ("no data, not ready") disappeared once we clarified PDFs, spreadsheets, and paper are enough. The reusable line that worked, now in the CRM: *"If you can hand it to a new employee on day one, we can work with it."* Customers consistently believe they're behind on AI because their data is in PDFs/Excel — that belief is the opening, not the obstacle.

### L3. A narrow wedge workflow sells; a platform pitch stalls
ILUM call #1 was a broad ops-intelligence pitch → traction came only when scope narrowed to one workflow (snake BOM automation, 40% of their production). After seeing a demo video, ILUM **doubled the contract scope and dollar value** before signing.

### L4. Champions compound
Pilot #3 (Roll Froz) came from a pilot #1 champion referral. Łukasz (PerfectData) opened the entire Mago Group and asked to reuse our investor-update email format with his own network. Bob (MARS Supply) volunteered a customer referral list and three association intros after one call.

### L5. Regulatory tailwind in the beachhead market
Poland's mandatory KSeF e-invoicing regime creates the identical invoice-attribution pain at every Polish manufacturer — a repeatable, low-friction wedge (already deployed once, being deployed again).

### L6. Lower the entry cost or lose the enterprise
Mitsubishi: a 2–6 week trial is already too much commitment before proof of value. Response: zero-integration sample dashboard behind a login link. Also learned the buyer map: plant manager/GM owns floor pain; problems only reach VPs as crises; the CFO office is structurally disconnected from the floor.

---

## 3. Pivots — what we changed and the evidence that drove it

| # | From → To | Evidence |
|---|---|---|
| P1 | "Capital projects" positioning → **post-construction ramp & operations intelligence** | Infineon polite no: Dresden construction done, "80% of decisions made" — buyer heard "construction," not ramp. Lesson recorded in CRM: *lead with post-construction ramp to steady-state.* |
| P2 | Mining/geology archives → **deprioritized; focus mid-market manufacturing** | Frank call (May 10): small buyer pool, majors self-build, every deposit bespoke. Manufacturing shows the opposite: repeatable workflows across plants. |
| P3 | US enterprise-first → **Poland beachhead, then US mid-market** | 2 of 3 paid pilots in Poland; KSeF mandate; warm network density; founder on-site (3-week Poland trip in progress). US/Canada pipeline maturing behind it. |
| P4 | Pure SaaS → **AI-native service-first (forward-deployed engineers), converting to subscription** | Roll Froz's stated fear: being "left with something unmaintainable or unaffordable." Split today ~60–70% service / 30–40% product, shifting toward product with each deployment. |
| P5 | Broad ICP → **$10–500M revenue, high-mix, ERP+MES, multi-plant/family-owned manufacturers** | Pattern across ILUM, Mago, Roll Froz, Conestoga; distributed plants = more disconnected systems = stronger fit (Omni call, Jul 1). |

---

## 4. Pilot traction detail

| Customer | Workflow | Commercials | Result / status |
|---|---|---|---|
| ILUM | Light-planner PDF/DXF → auto-proposed BOM → constructor approval → Excel export | $7,500 pilot, 50/50 on signature/delivery; ~$1K/mo subscription intent; ~$100K/yr expansion (ERP/warehousing) | KPI: BOM cycle 2–3 weeks → 2–3 days; 80%+ standard lines auto-proposed. Contract scope doubled after demo. Data handover + on-site visit underway |
| Mago Group / POSM | KSeF/Enova invoice-to-project matching, credit-card correlation, auto-approval ≥80–90% confidence | Pilot deployed; largest user base on platform; 6-plant expansion scope | Live data access (WireGuard + view-only Enova) being finalized |
| Roll Froz | Quote-to-capacity agent (inbound order email → stock + capacity check → margin-priced quote draft) | ~€15K indicative pilot | Proposal delivered week of Jul 28; in-person discovery during Poland visit |
| Conestoga Meats | Document controls (SharePoint), then cost management (CSB ERP) phase 2 | 60-day fixed-fee pilot | In PMO approval; customer inverted our phasing to dodge finance/IT gatekeepers — their idea, faster path |
| Mitsubishi Electric | Zero-integration sample-data dashboard | Entry offer | Follow-up workshop sent Aug 3 |

**Supporting proof points used in customer calls:** early platform version at T1 Energy (NYSE-listed) saved ~40 analyst hours/day; proprietary tooling cuts token cost ~5–10x vs. raw LLM usage. **Market frame:** US spent $224B on new factories last year (3x 2019); 98% of projects over budget or behind schedule, average overrun 79%.

---

## 5. What investors can verify

- ILUM confirmed (Jun 10 call) they are **referenceable to investors now**.
- Customer reference contacts already shared with one fund (Omni Ventures diligence).
- CRM shows systematic pipeline management: 30+ prospects with priority tiers (1aa/1a/1b/1c), next steps, and dated follow-ups.
- Standardized discovery questionnaire (3–5 questions across technical/use-case/business) run across 10+ conversations to build a comparable insight base (pipeline review, May 26).

---

*Compiled Aug 10, 2026 from Granola meeting notes, Airtable CRM, and Gmail threads. Figures quoted are as stated in the underlying call notes; where sources differed, the most recent or most conservative figure was used.*
