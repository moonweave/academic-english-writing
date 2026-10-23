# Selection rationale and stopping rule

Checked 2026-10-23. This patch distinguishes documented research influence/attention from editorial prose quality. Eight core papers meet both criteria at the stated passage scope; three auxiliary papers remain for specialist needs. No model weights were trained. All selections remain provisional pending the user's writing preferences.

## Two independent selection questions

1. **Why is the research worth consulting?** Record a primary institutional highlight, formal recognition or Crossref reference count. Recent here means 2024–2025 relative to this inspection date, not necessarily currently trending. Institutional press releases establish promotion by the institution, not independent consensus or demonstrated adoption. Raw counts are dated database observations, not comparable impact scores across ages and fields.
2. **Why use this prose?** Inspect the accessible passage in context for information order, grammatical relationships, defined referents and claim conditions. The table below records the curator's local assessment and a transfer risk. No source was selected merely because it appeared in Nature or Science. Neither citations nor Nobel recognition certify writing quality; no external best-written-paper award is claimed.

## Core selection record

Crossref counts below were read directly from its public work API on 2026-10-23; [the snapshot](attention-snapshot.json) records DOI, exact returned title, count and endpoint. Counts represent indexed citing records, not a comprehensive citation total, and will change. They support influence/uptake within this candidate set, without a percentile or a universal threshold.

| ID / paper | Research influence or attention evidence | Editorial prose assessment / transfer risk | Inspected scope |
| --- | --- | --- | --- |
| M1 Sun 2012 | 5,417 Crossref citing records | Concession places emphasis on the finding; named networks carry distinct mechanism verbs. Risk: confident mechanistic present tense needs evidence in a new study. | Named opening and mechanism paragraphs in author-hosted publisher PDF |
| M2 Novoselov 2004 | 63,645 Crossref records; [Nobel scientific background](https://www.nobelprize.org/uploads/2018/06/advanced-physicsprize2010-2.pdf) discusses this graphene work | A physical requirement precedes the obstacle; measurements precede the explanatory model. Risk: model adequacy is not uniqueness. | Named passages in 2004 author preprint v1, not verified publisher wording |
| M3 Zhao 2024 | 190 Crossref records; [Georgia Tech research highlight, 2024-01-03](https://news.gatech.edu/news/2024/01/03/researchers-create-first-functional-semiconductor-made-graphene) | The material label is tied immediately to its physical state. Risk: the abstract's broad comparisons and closing suitability claim need their own evidence; do not imitate them automatically. | Publisher abstract only; body behind subscription |
| P1 Guerre 2020 | 645 Crossref records | Attributed conflicting findings stay separate from possible explanations; benefit and cost remain adjacent. Risk: a review summarizes others' evidence. | Named minireview subsections in Europe PMC XML |
| P4 Cheng 2024 | 102 Crossref records; [RIKEN press release, 2024-11-26](https://www.riken.jp/en/news_pubs/research_news/pr/2024/20241122_1/index.html) and [RIKEN follow-up, 2025-03-27](https://www.riken.jp/en/news_pubs/research_news/rr/20250327_1/index.html) | A stability predicate carries its exception in the same clause. Risk: dense chemical noun phrases and promotional novelty wording are not general language targets. | Abstract reproduced by author institution; PDF body retrieval unreliable |
| E1 Pazos 2025 | 109 Crossref records; [NUS-authored release, 2025-03-27](https://www.eurekalert.org/news-releases/1078569) | The operating condition bounds capability; component intervention precedes its added function. Risk: device-level evidence does not establish whole-system efficiency. | Named abstract and Main passages inspected in publisher text during initial curation |
| E2 Indiveri 2011 | 1,223 Crossref records | Functional responsibilities precede circuit details; comparison uses consistent axes. Risk: a research paragraph rarely needs the full review taxonomy. | Named sections in publisher full text |
| E3 Shannon 1948 | 56,032 Crossref records for Part I only; [Bell Labs retrospective](https://www.nokia.com/bell-labs/publications-and-media/publications/so-rices-contributions-to-shannon-theory/) identifies its foundational influence | Definitions persist through a decomposition; reasons for a mathematical choice perform distinct jobs. Risk: historical framing and theory exposition do not dictate modern experimental prose. | Introduction of corrected reprint |

The local prose assessments are editorial judgments by the curating agent, not independent human reviews or claims that whole papers are uniformly excellent. For new M3 and P4, only abstract patterns enter the library; neither has been promoted to a body-text exemplar. Two accessible, bounded additions are more useful than unverified full-text claims.

## Auxiliary selection record

| ID | Retained use | Why outside the core |
| --- | --- | --- |
| P2 Zheng 2024 | Temporal sequence, alternative checks, ordered DSC procedure | Relevant inverse-vulcanization argument; awkward collocations make it unsuitable as a general grammar target. External attention was not established. |
| P3 Hojo 2026 | Synthetic purpose and characterization reporting | Local methods coverage; no established influence/attention evidence gathered. Recency alone is insufficient. |
| E4 Firlej 2023 v1 | ADC stimulus conventions and component power accounting | Useful measurement reporting in an author preprint; no external attention case established here. |

The auxiliary label records this curation's evidence, not a finding that these papers are scientifically unimportant. Preserve their existing locators, scope and limits.

## Not included in the pattern library

- Xu 2025, [hierarchical core-sheath hydrogels](https://doi.org/10.1038/s41467-024-55677-x): removed from the initial starter. Abstract-only inspection was insufficient for a stronger prose-quality judgment; broad evaluative wording adds little beyond the selected materials examples.
- Yan et al. 2022, [mechanochemical inverse vulcanization](https://doi.org/10.1038/s41467-022-32344-7): inspected Introduction and Discussion through Europe PMC XML (PMC9381570). Useful application limitations, but recurring grammar/collocation problems make it a weaker language exemplar and its process narrative overlaps the selected polymer case.
- Montarnal 2011, [silica-like organic networks](https://doi.org/10.1126/science.1212648): attractive abstract-level contrast, but publisher full text was unavailable. An abstract is insufficient for the intended section-level analysis.
- White 2001, [autonomic healing](https://doi.org/10.1038/35057232): bibliographic record confirmed; body text not obtained. Scientific importance alone cannot justify style selection.
- Shen 2017, [coherent nanophotonic circuits](https://doi.org/10.1038/nphoton.2017.93): inspected opening of the [author-hosted 2016 v1 preprint](https://ciqm.harvard.edu/uploads/2/3/3/4/23349210/shen2017.pdf). Version differs from the published paper, and the inspected contribution overlaps existing architecture/scope patterns. Do not present preprint wording as verified final prose.

## Why stop at eight core and three auxiliary sources

The core now spans materials, polymer chemistry and electronics, research/review/theory, established influence and three institutionally highlighted 2024–2025 studies. Fourteen core patterns cover the shared rhetorical needs; seven auxiliary patterns fill concrete methods and measurement gaps. Adding two abstract patterns corrects a specific coverage/attention gap without pretending that eleven is a measured optimum.

Reject redundant additions, inaccessible body-text claims and citation-based prose rankings. Add another paper when it contributes a missing writing decision, has inspectable supporting prose, and has a recorded influence/attention case if presented as core. RF measurement narratives, broader synthetic procedures, current 2026 highlights and user-specific style preferences remain gaps. This patch does not claim an exhaustive search of 2026 literature.

Existing comparative writing results remain unchanged: mixed preferences and ties, with no clear overall superiority. Corpus provenance and better retrieval labels are verified separately from any future writing-performance improvement.
