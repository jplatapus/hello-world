# NOEIN — Why We're Not In The Bucket

**Purpose:** Investors keep filing NOEIN under "everyone is doing AI for manufacturing." This memo is the counter-argument: a map of the actual field, the insight we earned that the field hasn't, and the specific structural reasons each class of competitor cannot follow us. Built from 35+ customer conversations (Apr–Aug 2026) plus external market research.

---

## 0. Steelman the objection first

The investor is right about one thing: "AI + factory" is crowded. Industrial AI is a multi-billion-dollar category with hundreds of funded companies; $1–6M seed rounds "prove entry, not dominance" ([New Market Pitch](https://newmarketpitch.com/blogs/news/industrial-ai-funding-trends)). If NOEIN were "a copilot that answers questions about factory data," the bucket would be deserved.

The rebuttal is not "we execute better." It is: **the crowd is all competing for the same ~quarter of manufacturing — the plants that are already digital. Our customers are the other three-quarters, and every existing architecture is structurally locked out of them.**

---

## 1. The field, mapped by its hidden assumption

Every competitor class embeds an assumption about what a factory already has. That assumption is each one's lockout.

| Bucket | Examples | Hidden assumption | Why they're locked out of our market |
|---|---|---|---|
| Enterprise ontology platforms | Palantir Foundry, C3.ai | $500K+/yr budget, 6–12 month patience, internal data teams | Mid-market contracts run [$500K–$2M/yr and implementation exceeds license cost in year one](https://www.bdemerson.com/article/palantir-cost). A $7.5K pilot is not a deal they can economically originate, staff, or service. Their FDEs cost [$300–550K each](https://getperspective.ai/blog/2026-fde-hiring-trends-what-1000-job-posts-reveal). Going down-market is P&L-dilutive for a company being rewarded for enterprise multiples. |
| Sensor / IIoT analytics | MachineMetrics, Oden, Sight Machine, Augury, Guidewheel | Instrumented, connected machines | The field consolidated from [200+ IIoT platform vendors](https://www.machinecdn.com/blog/state-of-iiot-2026/) precisely because the addressable set of instrumented plants was smaller than everyone modeled. A paper-and-Excel factory has nothing to plug their product into. |
| Shop-floor copilots / agent layers | QAD Redzone, ChampionAI, Quindi, Tulip | A working, integrated MES/ERP underneath | Only [8% of plants run a commercial MES; 54% run on paper and spreadsheets](https://iot-analytics.com/mes-vendors-replace-pen-paper-spreadsheets/). Even where MES nominally exists, [only 23% have fully integrated it](https://www.marketscale.com/industries/industrial-iot/93-of-manufacturers-have-mes-but-only-23-have-fully-integrated-it-rockwell-automation-finds). A copilot on top of nothing is nothing. |
| Vertical shop OS | Uptool (CNC quoting/shop mgmt) | One vertical, one workflow, rip-and-replace of process | Wins a niche; can't follow the customer across workflows. Our same platform runs BOM generation (lighting), invoice attribution (retail displays), and quote-to-capacity (frozen food) — the expansion revenue lives *across* workflows. |
| Horizontal agent/RPA startups | generic agent platforms; Factor (post-mortem) | Distribution and trust can be bought with ads | Factor — agentic sourcing, backed by Google Gradient — died on paid acquisition and supplier onboarding, pre-LLM. Its own investor is now in our data room, told us directly: *"what NOEIN is doing was not possible pre-LLM."* Right thesis, wrong decade, wrong distribution. |
| Lab + consultancy alliances | OpenAI×Bain, Anthropic×Deloitte | Fortune-500 budgets | [$1.5–10B services JVs](https://www.marktechpost.com/2026/05/20/what-is-a-forward-deployed-engineer-the-ai-role-openai-anthropic-and-google-are-hiring-in-2026/) aimed at global enterprises. Nobody is flying a Deloitte team to a 1,200-person shelving group in Mazowieckie. |

**The empty quadrant:** document-native (works from paper up), mid-market ($10–500M revenue), multi-workflow, champion-distributed, EU-regulation-timed. That's where NOEIN sits, alone so far. Not because it's hidden — because until ~24 months ago it was *technically unservable*, and it remains *economically unservable* for everyone whose cost structure was built for the digital quarter.

---

## 2. The earned insight (our "secret")

> **Messy data is not the barrier to AI in manufacturing. It is the market — and it is the moat.**

Three claims, each falsifiable and each backed by our own field evidence:

**2a. The "not ready" majority became addressable only when LLMs made unstructured mess machine-readable.**
54% of plants run operations on paper/spreadsheets. Gartner-cited industry consensus says [data readiness is the #1 reason manufacturing AI fails](https://erp.today/manufacturers-struggle-with-ai-readiness-despite-widespread-exploration/) — which is true *for every architecture that requires structured data*. Ours doesn't. Our pilots ingest light-planner PDFs, DXF drawings, color-coded Excel from a construction team, paper photos, and a 20-year-old Polish ERP used at 20% of capacity. The technology window for this opened in ~2023–24. The market's mental model hasn't caught up: prospects still open with "we have no data, we're not ready for AI" (FUJI, verbatim) — and the objection dissolves in one call.

**2b. The New-Employee Test.**
Our qualification doctrine, coined in the field and now in our CRM playbook: *"If you can hand the job to a new employee on day one, we can work with it."* Everyone else's funnel disqualifies on data readiness; ours qualifies on *employability of the process*. This inverts the industry's funnel — the leads everyone else throws away are our ICP. That is a genuinely different company, not a better copilot.

**2c. Digitizing a workflow that never existed digitally creates the only copy.**
The processes we automate — BOM logic living in four constructors' heads, invoice attribution living in 15–30 email threads — were never in any system. When we encode them, we create the *first and only* digital record of how that factory actually runs. Switching cost isn't "export your data"; it's "your process now runs through us." No competitor can train on, scrape, or migrate data that never existed anywhere else. Each deployment adds to a cross-factory workflow corpus that makes the next deployment cheaper (already observed: KSeF invoice workflow built once, redeployed; small fine-tuned model matching frontier-model performance at ~5x lower token cost).

---

## 3. Six advantages, each with the reason it's hard to copy

**A1. Founder-market fit that is literally the customer and literally the incumbent.**
Jacek built, ran, and sold a YC-backed *food manufacturing* company ($25M raised, 2,000+ stores) — he has been the buyer persona. Paritosh built the digital twin at T1 Energy (NYSE-listed) *using Palantir* — he has been the expensive incumbent, from inside, and knows exactly which 80% of that playbook to delete. "We've been the customer and we've been Palantir" is a two-sided credential almost no team in the bucket has.

**A2. Distribution into owner-operated manufacturers is the scarce asset, and it can't be bought.**
Field evidence: pilot #3 came from pilot #1's champion. One champion (PerfectData) opened a $150–200M group and asked to reuse our update-email format with his own network. A 100-year-old distributor (MARS Supply) volunteered customer referrals (Toro, 3M, Kurt) and intros to two manufacturer associations after one call. Factor's post-mortem shows the counterfactual: paid acquisition into this market torches capital. Trust graphs compound; ad budgets don't. Founder is Polish-native, on-site (3-week deployment trip in progress), running WhatsApp groups with plant staff — this is the sales motion the market actually transacts on.

**A3. The wedge is regulation-timed, and we're standing on it as it fires.**
Poland's KSeF e-invoicing mandate went live [Feb 1 / Apr 1, 2026, with KSeF numbers required on bank transfers from Aug 1, 2026](https://www.ey.com/en_gl/technical/tax-alerts/poland-signs-into-law-mandatory-national-e-invoicing-system). Every Polish manufacturer now has the identical invoice-attribution pain, simultaneously, by law. We built the workflow once and are deploying it a second time. The EU's ViDA agenda points the same wedge at Germany, France, and beyond. US-centric copilots aren't positioned for this; Polish accounting vendors do compliance, not cross-system attribution.

**A4. Our demo is our deployment — sales cost collapses into delivery cost.**
Because we ingest whatever exists, we build working demos from the prospect's own raw exports in days (Rollforce: files→demo→proposal inside two weeks; ILUM: doubled contract scope and value after one demo video; Mitsubishi entry: zero-integration dashboard behind a login link). Competitors who need clean data can't demo without a paid integration project first. Our CAC and our COGS are the same motion, and it's already producing referrals.

**A5. Economics that work at $7.5K and compound toward product.**
We can profitably originate at $7.5–15K pilots because ontology mapping is productized (24 standardized factory data fields, agents that map ERP data models) and inference is optimized (~5–10x cheaper process execution vs. raw LLM usage). Service/product mix ~60-70/30-40 today, shifting with each deployment as workflow templates accrete. The FDE model itself was just validated as the consensus playbook [by a16z and the labs themselves](https://getperspective.ai/blog/why-every-ai-startup-needs-forward-deployed-engineering-function-2026) — but they run it at $350–550K per engineer against F500 accounts. We run it where they can't afford to.

**A6. The compounding asset: a cross-factory workflow corpus nobody else is collecting.**
Every deployment captures how a real mid-market factory actually runs — in the exact segment where that knowledge has never been digitized. Per-client RL environments deepen switching costs; cross-client patterns (anonymized) cut the next deployment's cost. The 54% is not just a market; it's an untapped training distribution, and first movers with trust get exclusive access to it.

---

## 4. The rebuttal card (say these in the meeting)

| When they say | Say |
|---|---|
| "Palantir will move down-market." | Its mid-market contract floor is ~$500K/yr and implementation exceeds license cost; its FDEs cost $300–550K each. Serving a $7.5K-entry customer is P&L-dilutive at a 600%+ stock run. They've had 20 years to go down-market and have moved *up* every time. Our CTO deployed Palantir at a NYSE manufacturer — we know precisely where its floor is. |
| "You're a GPT wrapper; the labs will eat you." | The labs sell tokens and $B consultancy JVs aimed at the F500. Our work is WireGuard tunnels into 20-year-old Polish ERPs, view-only Enova accounts, computer-use agents doing exports when the API license costs too much, and three weeks on-site earning the trust of a family owner. Mitsubishi's own alternative was "self-build with OpenAI" — their exec told us the evaluation burden alone makes that a non-starter. |
| "Vertical SaaS already owns these niches." | A shop-OS wins one workflow in one vertical and stops. Our platform is already running three unrelated workflows in three verticals (BOM/lighting, invoices/retail displays, quotes/food) — the account expansion *is* the product. |
| "AI services don't scale." | Services-led growth is now the consensus enterprise-AI playbook (a16z; OpenAI×Bain; Anthropic×Deloitte). Ours converts: workflow #2 of KSeF cost a fraction of workflow #1, token costs are engineered 5–10x down, and every pilot has a scoped subscription phase behind it (~$500K near-term ARR, ~$1.5M qualified pipeline). |
| "Where's the moat at pre-seed?" | Three compounding ones, all already observable: (1) the only digital copy of each customer's core workflows, (2) a champion referral graph that produced pilot #3 at zero CAC, (3) a regulatory wedge we've productized while the mandate is live. Ask our pilots — ILUM has agreed to take investor reference calls. |
| "Why now?" | Two clocks started recently and we're timed to both: LLMs made paper-and-PDF factories machine-readable (~2023–24), and the EU began legally forcing structured e-invoicing onto every manufacturer (Feb 2026–). The 54% became servable and got a compliance deadline in the same 24 months. |

---

## 5. One-sentence versions (pick per audience)

- **Contrarian:** "AI-for-manufacturing isn't crowded — it's crowded on the paved quarter of the market. We're building the road where the other 54% of traffic actually is."
- **Insight-led:** "Everyone treats messy data as the barrier; we discovered it's the market — and once you digitize a workflow that never existed digitally, you own the only copy."
- **Credential-led:** "We've been the customer (built and sold a food manufacturer) and we've been the incumbent (deployed Palantir at a NYSE manufacturer). We're building what both of those jobs proved was missing."

---

### External sources
- [IoT Analytics — 54% of plants on paper/spreadsheets; 8% commercial MES](https://iot-analytics.com/mes-vendors-replace-pen-paper-spreadsheets/)
- [Rockwell via MarketScale — 93% have MES, 23% fully integrated](https://www.marketscale.com/industries/industrial-iot/93-of-manufacturers-have-mes-but-only-23-have-fully-integrated-it-rockwell-automation-finds)
- [BD Emerson — Palantir cost structure](https://www.bdemerson.com/article/palantir-cost) · [Peerspot pricing experience](https://www.peerspot.com/questions/what-is-your-experience-regarding-pricing-and-costs-for-palantir-foundry)
- [EY — Poland KSeF mandate timeline](https://www.ey.com/en_gl/technical/tax-alerts/poland-signs-into-law-mandatory-national-e-invoicing-system) · [ecosio — KSeF 2026 details](https://ecosio.com/en/blog/e-invoicing-in-poland-7-topics-you-need-to-know-in-2026/)
- [Perspective AI — FDE hiring +1,000% YoY; comp bands](https://getperspective.ai/blog/2026-fde-hiring-trends-what-1000-job-posts-reveal) · [MarkTechPost — lab FDE/services alliances](https://www.marktechpost.com/2026/05/20/what-is-a-forward-deployed-engineer-the-ai-role-openai-anthropic-and-google-are-hiring-in-2026/)
- [MachineCDN — IIoT vendor consolidation](https://www.machinecdn.com/blog/state-of-iiot-2026/) · [New Market Pitch — industrial AI funding](https://newmarketpitch.com/blogs/news/industrial-ai-funding-trends)
- [ERP Today — data readiness as #1 AI failure cause](https://erp.today/manufacturers-struggle-with-ai-readiness-despite-widespread-exploration/)
- Internal: Granola call notes (ILUM, Mago/POSM, Roll Froz, Conestoga, Mitsubishi, MARS Supply, FUJI, Omni/Factor post-mortem), Airtable CRM.

*Compiled Aug 12, 2026.*
