# Operating an innovation team: a handbook

**Who this is for:** the leader or sponsor of a small innovation unit (roughly 5-50 people) inside a larger organization.

**How to use it:** each practice has a lesson ID (`L#`) pointing to `../synthesis/operating-model-lessons.md` and an evidence grade. Grades come from the knowledge base: **strong**, **moderate**, **weak**, **inference** (see `../METHODOLOGY.md`). Treat anything below *moderate* as a hypothesis to test in your own setting, not proven best practice. No source in this base compares any innovation model with a counterfactual, so none of what follows is guaranteed to work.

---

## 1. Before you launch: the conditions check

Run this before hiring anyone. Answer each item in writing.

| Question | Healthy answer | If the answer is no |
|---|---|---|
| Does funding survive one bad quarter and one new CFO? | Multi-year commitment, ideally tied to revenue or a stated mission | Name the substitute funding logic and its failure date [L1, L4] |
| Who is the executive sponsor with budget authority? | One named person who will defend the unit | Do not launch; the recurring decline pattern is ownership/funding shock [L19] |
| Who is the first customer inside the business? | A named business owner who wants the output | Define the exit route now (licensing, spin-out, sale) [L14, L15] |
| What is the mandate? | Either a dated mission *or* an open exploration area, not both | Pick one. Dated need: mission mode. Unknown space: long-horizon mode [L2, L5] |
| What is your end state? | Written: reintegrate, spin out, or sunset | Write one anyway; ending without a plan is the common failure [L18] |

**Why it matters:** the long-lived centers (Bell Labs, DARPA, Skunk Works, GE/DuPont) all had funding tied to the parent's revenue or a government mission. Funding *stability* mattered more than size: Bell Labs took a small share of Bell System revenue [L1, moderate]. If you lack the original conditions, the evidence says to replace the funding logic explicitly, not to copy surface features [L4, inference; L22].

---

## 2. Design the unit

### 2.1 Pick a mode

| | Mission mode | Exploration mode |
|---|---|---|
| Use when | There is a dated, named need | The problem space is unknown |
| Models | Skunk Works, Apollo, Rad Lab | Bell Labs, HHMI/Janelia |
| Funding | Project funding against a customer | Fund people and long horizons [L2] |
| Selection | Customer, date, defined success [L5] | Judge people and direction; expect a heavy upper tail [L2] |
| Watch for | Schedule/cost overrun (the A-12 ran about a year late and over cost) [L5] | Drift from any business use [L14] |

HHMI-style people funding is the best-quantified result in the base: about +39% publications, +55% top-5% and +97% top-1% for HHMI investigators versus matched prize-winner controls (69 vs. 348, matched on observables, not randomized) [L2, moderate-to-strong]. It concerns individual investigators, not campuses or corporate labs.

### 2.2 Give authority a single owner

- One accountable leader per program with authority over scope, staffing and customer contact [L3, moderate; Skunk Works Rules 1, 11, 12].
- Pair authority with administrative flexibility: DARPA's program-manager model works alongside special contracting and hiring authorities. Copying only the title does not work [L3].
- Separate advice from authority in reviews: peers give input, one named owner decides (Pixar's Braintrust) [L23, moderate].
- Staff each venture with a dedicated, empowered leader. Small size alone is not the mechanism [L25, weak].

### 2.3 Team shape

- Keep teams small with controlled outside interference, but add an integration function when you scale (Apollo) [L9].
- Recruit through a credible network. PARC's lab was built through one leader's ARPA/SRI relationships [L10: strong for that case only].
- Co-locate if cheap, but do not expect architecture to produce collisions on its own [L11, weak].
- Own the work end to end where possible: design, build and test inside one team [L8a, weak].
- Protect a line to senior leadership and a host organization that absorbs risk for you (Rad Lab/MIT, JPL/Caltech) [L13, moderate].

---

## 3. The operating rhythm

### 3.1 Intake (every project)

Require written answers before work starts [L5]:
1. What are you trying to do, in plain language?
2. How is it done today, and what is new here?
3. Who cares, and what changes for them if it works?
4. What are the risks and the riskiest assumption?
5. What does it cost, how long does it take?
6. What are the interim milestones and how will we check them?
7. Who is the named business owner who will take the result?

These are adapted from the Heilmeier catechism (the Caltech page lists seven questions; this list is a paraphrase, not the original wording). The catechism is a practitioner heuristic with little outcome evidence [L5, weak-to-moderate]. Question 7 is this handbook's addition; it targets the dominant failure mode (§5).

For consumer or customer-facing work, write the customer outcome first (Amazon's PR/FAQ), but do not treat it as sufficient. The Fire Phone passed that process and failed [L24, weak].

### 3.2 Early test

- Attack the riskiest assumption first, on a small budget [L6].
- Set kill criteria in advance, in writing, at intake (X's Operating Manual does this) [L6].
- Stage the proof: Skunk Works built the small Have Blue demonstrator before the F-117 [L6].
- Run a cheap parallel hedge when one assumption could sink the program. Los Alamos pursued implosion alongside the gun design, but scaled it up late; start hedges earlier than they did [L7, moderate].

### 3.3 Gates

- Review at defined gates against the written criteria, not against enthusiasm.
- Make stopping a normal outcome. Do **not** quote a kill rate as a target: X's widely cited "98% killed early" figure is unsupported. X's own Operating Manual describes no reward for killing [L6].
- Keep options open while learning is cheap and late change is costly (Toyota's set-based engineering), but note that evidence for it outside Toyota is thin [L26, weak-to-moderate].

### 3.4 Slack and exploration

- Reserve protected exploratory time and norms for sharing and platform reuse [L27, weak]. 3M's 15% rule is descriptive, and its origin and conditions are unverified.
- Do not apply efficiency metrics unchanged to exploratory work. 3M's Six Sigma era coincided with a falling new-product share, though causation is contested and R&D funding was held flat, not cut [L28, weak-to-moderate].

### 3.5 Security and compartmentalization

Control outward information flow, share freely inward. The evidence is mixed and weak (Manhattan Project) [L12]. Use it only where secrecy is a real requirement.

---

## 4. Portfolio management

- Judge the portfolio on power-law logic, not average project return. This is inference: Alphabet's Other Bets lost $4.1B (2023), $4.4B (2024), $7.5B (2025, including a $2.1B Waymo compensation charge) against a Waymo valuation near $126B, and no source computes net portfolio return [L8, weak/inference].
- Tolerate failure in individual projects, but make it visible and documented.
- Review the portfolio for drift after growth, acquisition or cost pressure (Pixar post-Disney, Toyota). Set guardrails on mix, such as a floor on exploratory work [L29, inference].
- Expect your best work to be reabsorbed. X's successes have gone back into Google (Brain, Everyday Robots, Intrinsic) [L18].

---

## 5. Transition: the hand-off is where projects die

The most repeated failure in the base is not invention but hand-off [L14, strong for PARC, moderate elsewhere].

**Rules**
1. **Name the receiving owner at intake**, not at the end [L14].
2. **Judge outputs on their own business model.** Xerox judged PARC work by the copier model; the spin-offs that succeeded built different models [L14].
3. **Match the product to the buyer.** The Star sold to office-systems buyers at about $16,595 per seat (about 25,000 units); the "Xerox could have beaten the IBM PC" story is contested [L14].
4. **Count a transition only if funding continues.** GAO reclassified DARPA's biofouling program because funding had ended [L14]. Use that definition.
5. **Choose the exit route early:** internal transfer, licensing, or spin-out. For spin-outs, the one 35-venture study (Chesbrough 2003) associates a Xerox-insider CEO and parent equity stake with worse results and a higher VC share of board seats with better. Limit the parent's control [L16, moderate].
6. **Treat IP policy as part of the system.** The 1956 AT&T decree's royalty-free licensing is associated with about 17% more follow-on innovation by *others*. That measures spillovers, not benefit to the lab [L17, strong]. Decide deliberately what to license, publish and hold.
7. **Plan reintegration.** The one skunkworks-copycat study (TechPlus) won the market and lost the organization [L18].

---

## 6. People, culture, integrity

- Hire for the community you are building and reward publication/sharing norms where research integrity matters [L10, L27].
- Protect research-integrity systems (data review, replication, authorship rules) as the unit shrinks or comes under pressure [L20, weak; Schön case at Bell Labs].
- Build institutions that outlast the founder: documented process, second-line leaders, a sponsor beyond the founding executive [L21, weak/inference].

---

## 7. Measurement

The profiles found little robust outcome measurement. Use inputs *and* outcomes [L30, weak; 3M's Vitality Index lacks proven validity]. A starting set (the base's inference, not validated):

| Metric | Why |
|---|---|
| Share of projects with a named business owner at intake | Leading indicator for hand-off |
| Share transitioned *with continuing funding* | Honest transition rate [L14] |
| Time from start to first customer test | Speed to evidence |
| Kill rate with documented reasons (not a target) | Gate discipline [L6] |
| Follow-on funding or revenue | Outcome |
| Retention of key people | Culture health |
| Share of portfolio in exploratory work | Drift guardrail [L29] |

Pre-register metrics before the work starts. DARPA's transition tracking was found unreliable partly because "transition" had no common definition [L14].

---

## 8. Governance and failure watch

**Review cadence (suggested)**
- Monthly: project gates, kill/continue decisions, transition owners.
- Quarterly: portfolio mix, drift, sponsor check-in.
- Annually: mandate, funding logic, end-state plan. Ask what changed in ownership or budget.

**Early-warning signs** (from the decline pattern, correlational) [L19]:
- Sponsor or parent ownership changes.
- Budget cycle cuts hit long-horizon projects first (Everyday Robots was shut January 2023).
- Headcount falls faster than the project list.
- Outputs are judged only by the parent's current business.
- Unit loses its line to leadership.

**Anti-patterns**
- Copying surface features (isolation, a kill rate, 20%/15% time) without the funding and authority conditions [L4, L22].
- Crediting the model with outcomes the evidence only partly supports (DARPA and Moderna or Siri; PARC and Apple) [L22].
- Quoting unverified figures as targets (the 98% kill rate).
- Isolating a unit with no reintegration plan [L18].
- Declaring transition success when funding has ended [L14].

---

## 9. First 90 days

| Days | Do |
|---|---|
| 0-15 | Complete the conditions check (§1). Secure the sponsor, funding horizon and end-state document. |
| 15-30 | Choose mode (§2.1). Name authority holders. Write the intake template with the transition-owner question. |
| 30-60 | Run the first 2-3 projects through intake and the early test (§3). Set kill criteria in advance. Agree the metrics (§7). |
| 60-90 | Hold the first gate review. Name the receiving owner for every surviving project. Set the review cadence (§8). |

---

## What this handbook cannot tell you

- Which practice caused which outcome. Most evidence is single-case or correlational. The best quasi-experimental results concern funding structure (HHMI vs. NIH) and IP licensing (the 1956 decree) [Where the evidence is thinnest, lessons file].
- Whether newer models (focused research organizations, ARIA, Arc, Wellcome Leap) work. They have no outcome evidence yet.
- Whether a practice transfers to your sector, size or culture. Run each as an experiment with a written hypothesis and a review date.
