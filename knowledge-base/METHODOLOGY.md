# Methodology and limitations

## How this knowledge base was built

1. An automated deep-research workflow (search, fetch, claim extraction, adversarial verification) was run first. It produced **no usable output**: all 21 fetched sources came back empty because the environment's network policy returned 403 on every host (for example `www.darpa.mil`, `en.wikipedia.org`).
2. Parallel research agents then each took one center or group of centers and wrote a profile into `centers/` (plus one literature review into `synthesis/`), using web search only.
3. The synthesis files (`synthesis/operating-model-lessons.md`, `comparison-matrix.md`, `adoption-playbook.md`) were written from those profiles.

## Key limitation: no page was opened

Every profile cites URLs that appeared in search results, but **no agent could open and read the underlying pages**. Each file carries a header note saying this. Consequences:
- Citations show where a claim was seen in a search summary, not that the full source was read.
- Some items are flagged in-file as unverified, loosely cited, or not retrieved (examples: Kelly Johnson's full 14 rules; DARPA stealth and Grand Challenge claims; Google X's per-project loss figures; Fraunhofer founding year; Bell Labs 1% funding share).
- Source disagreements are listed in the files rather than resolved (for example Manhattan Project cost, Menlo Park closure date, Bell Labs Nobel counts).
- Known cleanup items: Bell Labs sources list has an item "23b" and bundled URLs; Google X sources 7 and 26 need re-checking.

## Evidence grades

Lessons are tagged strong / moderate / weak / inference. The grades describe the strength of the *evidence the profile found*, not certainty about the facts. "Inference" means the writer's judgment.

## Recommended next step

Allow outbound access to the key hosts (Wikipedia, `darpa.mil`, `lockheedmartin.com`, `nber.org`, `janelia.org`, `x.company`, `technologyreview.com`, `cia.gov`, `nasa.gov`) and re-run each profile so claims can be checked against the pages themselves. Network access is changed in the cloud environment's settings (environment menu, then Edit, then Network access).

## Status of coverage

Covered: Pixar/Amazon/3M/Toyota (centers file; not yet folded into the synthesis lessons), Bell Labs, Xerox PARC, Skunk Works, Google X, DARPA (+ARPA-E, IARPA, ARPA-H, ARIA), Edison/GE/DuPont/IBM, Manhattan/Rad Lab/Apollo, Janelia/Fraunhofer/FROs, academic literature.
Not yet folded into `synthesis/operating-model-lessons.md` or the comparison matrix: the corporate cultures profile arrived after the synthesis was drafted.
