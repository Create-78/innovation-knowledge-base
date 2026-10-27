# Cross-cutting operating-model lessons

> **Provenance warning.** This file synthesizes the center profiles in `../centers/` and the literature review in `research-literature-on-rd-organization.md`. Every profile was built from web-search result summaries only, because page fetching was blocked in the research environment (see `../METHODOLOGY.md`). Evidence grades below are inherited from the profiles and are mostly "moderate" or "weak". Citations point to the profile that carries the underlying source list, for example `[Bell Labs 7][8]` means sources 7 and 8 in `centers/bell-labs.md`. Treat nothing here as verified against a primary source.

Evidence key: **strong** = quasi-experimental or multiple independent sources; **moderate** = well-documented, consistent across sources, causal weight not isolated; **weak** = single case or anecdote; **inference** = this knowledge base's judgment.

## 1. Funding and mandate

**L1. Fund from a stable, mission-tied base, with an explicit sponsor.** [moderate]
- Bell Labs' freedom is linked to monopoly income and its decline to losing it [Bell Labs 9][13][17].
- GE and DuPont's fundamental research needed executive sponsorship and a protected budget; Stine had to win committee approval [Industrial 5].
- Google X faces repeated budget-cycle cuts to long-horizon bets (Everyday Robots 2023) [Google X 13][24].
- Janelia/HHMI-style long horizons are the best-evidenced funding model, but the evidence concerns HHMI investigators, not campuses [Institutes 1].

**L2. Fund people and long horizons when the goal is exploration.** [moderate] HHMI vs. NIH shows more high-impact output with long, failure-tolerant, people-based funding [Institutes 1]; the literature review grades this its strongest causal evidence [Literature].

**L3. Pair decision authority with administrative flexibility.** [moderate] DARPA's program-manager authority works alongside hiring and contracting flexibility (Other Transaction authority); copying only one is unlikely to work [DARPA 8][6]. Skunk Works shows the same pattern: one accountable leader with authority over scope, staffing and customer contact [Skunk Works 21][27].

**L4. Replace the funding logic explicitly if you lack the original conditions.** [inference] Bell Labs' monopoly [Bell Labs 17], Skunk Works' classified sole-sponsor context [Skunk Works 27] and mission labs' wartime urgency [Mission, "what doesn't transfer" sections] are conditions most firms do not have.

## 2. Selection and process

**L5. Force clarity up front.** [weak-to-moderate] Heilmeier-style questions and interim milestones at program creation [DARPA 3][4]; Skunk Works' named customer and fixed date [Skunk Works 11][13][17]; Apollo's concrete mission with the technical path chosen late after a multi-year comparison [Mission 20]. Note the Heilmeier catechism and Stage-Gate are practitioner heuristics with little outcome evidence [Literature].

**L6. Test the riskiest assumption first and make killing cheap.** [moderate, self-reported] X's "monkey first" rule and small early budgets [Google X 2][3][5]; the reported ~98% early kill rate is self-reported [Google X 4]. Skunk Works' staged proof (Have Blue before F-117) is the defense-industry analogue [Skunk Works 19][20].

**L7. Run cheap parallel hedges where one assumption could fail.** [moderate] Los Alamos' implosion group was set up before the gun-type plutonium design failed in 1944; Los Alamos was only ~4% of Manhattan spend [Mission 3][7][10].

**L8. Judge a portfolio on power-law outcomes.** [weak/inference] Inferred from Waymo's valuation against Other Bets losses [Google X 8][11][14]; no source computes net portfolio return.

## 3. Structure, people and culture

**L9. Small, empowered teams with controlled outside interference.** [moderate for design, weak for causation] Skunk Works Rule 3 text confirmed, but "size caused success" is anecdotal [Skunk Works 24][26]. Literature: small teams tend to disrupt, large teams develop (Wu, Wang & Evans), with a contested measurement [Literature].

**L10. Build a research community by recruiting through an elite network.** [strong] PARC's Computer Science Lab was built through Bob Taylor's ARPA/SRI network [PARC 13][18][19].

**L11. Co-location helps, but do not over-credit architecture.** [weak] Gertner stresses proximity; Owen-Smith finds mixed causal support [Bell Labs 9][11]. The Allen-curve 50 m figure is hard to trace [Literature].

**L12. Compartmentalize outward, share inward.** [weak] Mixed evidence from the Manhattan Project [Mission 1].

**L13. Give the lab a protected line to leadership and a host that absorbs risk.** [moderate] Rad Lab, Los Alamos/UC, JPL/Caltech [Mission 14][9][25].

## 4. Commercialization and transition (the most repeated failure mode)

**L14. Design the hand-off before the invention matures.** [strong for PARC, moderate elsewhere]
- PARC: Xerox judged spin-offs by its copier business model, while successful ones built different models [PARC 22][23].
- Industrial labs: Corfam, IBM's relational database, Menlo Park show different breaks in the chain [Industrial 10][29].
- DARPA: transition tracking was found unreliable by GAO (2015) and DOD has no common definition of "transition" [DARPA 23][10].

**L15. Keep research inside a business that is also the first customer, or pay for the missing link.** [moderate] Bell Labs [Bell Labs 5][12]; GE/DuPont tying science to existing platforms [Industrial 5][9][18]; PARC lacked an interface to the parent [PARC 18][19][22].

**L16. If spinning out, use outside CEOs, VC-style governance and room to experiment.** [moderate, one 35-venture study] [PARC 17]. Google X's insistence that graduates raise outside capital is consistent but contested (Verily) [Google X 13][14][20].

**L17. Treat IP policy as part of the innovation system.** [strong] The 1956 AT&T consent decree's royalty-free licensing is associated with ~17% more follow-on innovation by others; this measures spillovers, not benefit to the lab [Bell Labs 7][8].

**L18. Plan for reintegration and for the end state.** [weak-to-moderate] The one skunkworks-copycat study (TechPlus) won the market and lost the organization [Skunk Works 28]; the Rad Lab closed with projects seeded into successors [Mission 14][16].

## 5. Decline and durability

**L19. Shocks to ownership and funding, not lack of talent, track most decline stories.** [moderate, correlational] Bell Labs: divestiture, Lucent spin-off, later ownership changes [Bell Labs 13][23b][14]. Microsoft Research's Silicon Valley closure shows autonomy depends on the parent [Institutes 18][19]. Corporate science broadly receded (publications fell 1980-2006 while patent-measured value held) [Industrial 1][2].

**L20. Protect research-integrity systems as an organization shrinks.** [weak] The Schön case [Bell Labs 16].

**L21. Build institutions that outlast the founder.** [weak/inference] Menlo Park ended with its move; GE's lab outlived Whitney [Industrial 14][18].

**L22. Do not credit one agency with whole technology lineages, and do not copy surface features.** [moderate] Moderna and Siri show partial DARPA roles [DARPA 20][21][22]; Fraunhofer needs a dense SME base and a restructuring-capable state [Institutes policy commentary, weak].

## 6. Corporate operating cultures (Pixar, Amazon, 3M, Toyota)

Source: `../centers/corporate-innovation-cultures-pixar-amazon-3m-toyota.md` (40 sources, all search-summary only; none graded strong).

**L23. Separate advice from authority in exploratory reviews.** [moderate] Pixar's Braintrust gives voice without veto and names one accountable owner [Corporate 3][4][7]; no outcome studies.

**L24. Write the customer outcome before building.** [weak] Amazon's PR/FAQ and memos are testimonial evidence; the Fire Phone ($170M write-down) shows it is insufficient [Corporate 12][17][18].

**L25. Staff ventures with a dedicated empowered leader, not small size alone.** [weak] Secondhand Amazon notes [Corporate 11]. Reinforces L3 and L9.

**L26. Keep options alive until learning justifies narrowing, when late change is costly.** [moderate] Toyota set-based engineering; transfer beyond Toyota is difficult [Corporate 33][35].

**L27. Protect exploratory slack, with sharing norms and platform reuse.** [weak] 3M's 15% time evidence is descriptive; no peer-reviewed output measure was found [Corporate 21-23].

**L28. Do not apply efficiency metrics unchanged to exploratory R&D.** [moderate, causality contested] 3M's Six Sigma era saw new-product share fall while margins rose [Corporate 29][30].

**L29. Watch for drift after growth, acquisition or cost pressure; set portfolio guardrails.** [inference] Pixar post-Disney, Toyota [Corporate 8][10][37].

**L30. Measure outcomes, not only inputs.** [weak] 3M's New Product Vitality Index; predictive validity not found [Corporate 30].

## Where the evidence is thinnest

- No source gives a controlled comparison of any center against a counterfactual [DARPA open gaps].
- Many headline figures are self-reported (X's kill rate, FRO results, Fraunhofer impact studies).
- New models (FROs, ARIA, Arc, Wellcome Leap) have no outcome evidence yet [Institutes].
