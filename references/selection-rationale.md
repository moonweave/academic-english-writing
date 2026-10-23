# Selection rationale and stopping rule

Date: 2026-10-23. Editorial selection for materials, polymers, and electronic engineering. This is not a survey of all excellent scientific writing or a test of scientific correctness.

## How quality was judged

Prefer passages with a specific question, an interpretable comparison, visible observation/inference boundaries, coherent information order, and grammar that expresses the intended relation. Journal prestige, citation counts, and author reputation were not treated as writing-quality scores. Select local strengths; a scientifically important paper may contain awkward language or overstatement elsewhere.

The initial twelve candidates were screened to different depths. Seven papers entered the initial library. Revision added two papers specifically for synthesis/characterization and circuit measurements, plus a Methods pattern from an existing source: nine papers now supply nineteen patterns. “Full text accessible” does not mean every page was closely read. No language-model training was performed, no paper PDFs are distributed, and these seven selections are not claimed as the world's best-written papers.

## Included

| Paper | Why this passage earns a place | Scope |
| --- | --- | --- |
| Sun 2012 | Quantitative motivation and concrete mechanism exposition | Research letter; materials and polymers |
| Novoselov 2004 | Physical obstacle and observation-to-model progression | Author preprint; materials/electronics |
| Guerre 2020 | Conflicting literature and explicit trade-offs | Polymer minireview |
| Zheng 2024 | Time-dependent observations and artifact checks | Polymer domain argument; not a general grammar model |
| Pazos 2025 | Condition-dependent device claims and implementation scope | Device research |
| Indiveri 2011 | Functional decomposition and multidimensional comparison | Circuit review |
| Shannon 1948 | Precise definitions and justified mathematical representation | Theory; corrected reprint |
| Hojo 2026 | Synthetic modification and explicit characterization methods | Polymer-catalyst research; named local passages |
| Firlej 2023 preprint | Sweep conditions and component power accounting | SAR ADC measurements; versioned author preprint |

Source links and precise passage locators are in [the domain files](paper-patterns.md). The strongest models for concise argument construction in this set are the selected Sun, Novoselov, and Shannon passages; that is the curator's judgment, not an external award or ranking.

## Not included in the pattern library

- Xu 2025, [hierarchical core-sheath hydrogels](https://doi.org/10.1038/s41467-024-55677-x): removed from the initial starter. Abstract-only inspection was insufficient for a stronger prose-quality judgment; broad evaluative wording adds little beyond the selected materials examples.
- Yan et al. 2022, [mechanochemical inverse vulcanization](https://doi.org/10.1038/s41467-022-32344-7): inspected Introduction and Discussion through Europe PMC XML (PMC9381570). Useful application limitations, but recurring grammar/collocation problems make it a weaker language exemplar and its process narrative overlaps the selected polymer case.
- Montarnal 2011, [silica-like organic networks](https://doi.org/10.1126/science.1212648): attractive abstract-level contrast, but publisher full text was unavailable. An abstract is insufficient for the intended section-level analysis.
- White 2001, [autonomic healing](https://doi.org/10.1038/35057232): bibliographic record confirmed; body text not obtained. Scientific importance alone cannot justify style selection.
- Shen 2017, [coherent nanophotonic circuits](https://doi.org/10.1038/nphoton.2017.93): inspected opening of the [author-hosted 2016 v1 preprint](https://ciqm.harvard.edu/uploads/2/3/3/4/23349210/shen2017.pdf). Version differs from the published paper, and the inspected contribution overlaps existing architecture/scope patterns. Do not present preprint wording as verified final prose.

## Why stop at nine after revision

The nineteen patterns cover problem definition, quantitative motivation, comparison, experiment rationale, time evolution, alternative explanations, literature disagreement, trade-offs, architecture, and evidence-bounded claims across research, review, and theory. Another paper should fill a concrete uncovered need, not merely increase the count. Keep domain files separate so every edit does not load the whole collection.

This is a practical starting size, not an empirically proven optimum. Add a paper when a real drafting task exposes a missing pattern or the user identifies a preferred exemplar. The added passages address ADC measurement reporting and synthesis/characterization exposition; the DSC pattern covers ordered Methods prose. Remaining gaps include RF measurement narratives, exhaustive synthetic-procedure coverage, and journal- and author-specific voice preferences. The two added papers were selected for these local decisions, not claimed uniformly excellent. Attempts to retrieve older O-ATRP continuous-flow and perylene articles through Europe PMC failed; those texts were not treated as inspected sources.

## Operational depth and effectiveness

Revision expanded every existing pattern from a summary into a short source fragment, grammatical explanation, original application and limits. This is a change in teaching content, not by itself evidence of improved writing. The held-out comparison in evals/protocol.md defines a separate check; report its actual results and limitations, including ties or regressions.
