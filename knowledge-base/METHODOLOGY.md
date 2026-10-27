# Methodology and limitations

## How this knowledge base was built

1. An automated deep-research workflow was run first. It produced **no usable output**: all 21 fetched sources came back empty because the environment's network policy returned 403 on every host.
2. Parallel research agents then wrote one profile per center (plus a literature review) into `centers/` and `synthesis/`, using web search only. Synthesis files (lessons, matrix, playbook) were written from those profiles.
3. **Verification pass (2026-10-27).** Outbound access had been enabled. One agent per file re-opened the cited sources and better primary ones (company and agency sites, Nobel pages, NBER and journal abstracts, Wikipedia, 10-K filings, CIA and NASA history pages), corrected the profile in place, renumbered its sources, and replaced the old method note with a verification note. Synthesis files were then updated to match.

## What the verification pass changed

Material corrections, all reflected in the lessons: the HHMI-vs-NIH effect sizes (+39% / +55% / +97%, 69 vs. 348, not "2x/3x"); Google X's "98% killed" figure (unsupported) and per-project losses (not disclosed; Other Bets 10-K totals added); Bell Labs funding share, Nobel count (10 per Nokia, 11 per Wikipedia) and 2026 Nokia claims; Fraunhofer's funding split (88% contract research, base capped at a third); Manhattan Project cost basis and Los Alamos share; the Menlo Park closure date; the Chesbrough 2003 finding (insider CEO and equity stake correlate with worse results, not "outside CEOs"); Amazon single-threaded-team provenance; 3M R&D funding (held flat, not cut); DARPA budget, OTA history and the biofouling transition reclassification.

## Remaining limitations

- Some pages remained unreachable (for example 3M-hosted pages, WEF, Living Computers, some paywalled journals); claims resting on them are marked unverified in each profile.
- Several books were read only through excerpts or summaries: Gertner, Hounshell & Smith, Hiltzik, Smith & Alexander, *Creativity, Inc.*, Bryar & Carr.
- Wikipedia pages were sometimes read only in part; Wellerstein's Manhattan cost figures are second-hand.
- Source disagreements are listed in the files rather than resolved (Los Alamos share of Manhattan spend, DARPA headcount, Post-it 1973 vs. 1974, Prius design count).
- Not re-verified: Allen, Broad, Microsoft Research, Arc, ARIA staffing and Wellcome Leap details in the institutes profile; current Janelia budget; FRO status and launch dates; Waymo standalone losses; Wing deliveries.
- Effect sizes in the literature review for 15% and 17% figures rest on secondary summaries.

## Evidence grades

Lessons are tagged strong / moderate / weak / inference. The grades describe the strength of the *evidence the profile found*, not certainty about the facts. "Inference" means the writer's judgment.

## Recommended next steps

- Open the still-unverified primary sources listed in each profile's header (priority: the 1956-decree patent counts, Gertner's book, Hounshell & Smith, Catmull's HBR article beyond its introduction, Physics Today on compartmentalization).
- Re-check fast-moving facts (Alphabet 10-K, DARPA appropriations, Nokia research cuts, FRO roster) on a schedule.

## Status of coverage

Covered: Pixar/Amazon/3M/Toyota, Bell Labs, Xerox PARC, Skunk Works, Google X, DARPA (+ARPA-E, IARPA, ARPA-H, ARIA), Edison/GE/DuPont/IBM, Manhattan/Rad Lab/Apollo, Janelia/Fraunhofer/FROs, academic literature.
All profiles are folded into the synthesis (lessons L1-L30, plus L8a).
