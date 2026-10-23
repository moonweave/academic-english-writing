# Comparative results

Date: 2026-10-23. Three isolated writers completed the same three held-out synthetic briefs: no skill, old skill, and revised skill. Two independent agent evaluators received only the original requests/notes and anonymous outputs. Condition labels were revealed after both assessments completed. Exact model and sampling metadata were not captured; see run.json for the retained configuration and snapshot information.

## Actual preferences

| Case | Judge one | Judge two |
| --- | --- | --- |
| Materials abstract | Revised = old | Revised = old |
| Polymer Discussion | No skill = revised | No skill |
| Measured-circuit Results | Old | Old = revised |

All nine outputs met the requested word ranges. Neither judge identified a hard factual failure in any output. Omissions and minor wording concerns are retained in the full judgments; passing this gate does not mean every detail was equally explicit.

The abstract outputs using a skill made the measurement and interpretation limits more explicit than the no-skill output. The Discussion without a skill linked the missing control to the attribution problem particularly well. The revised Discussion was concise but could sound like an editorial status report when marking future tests. For Results, the old skill organized performance and accounting clearly; the revised skill placed fabrication context earlier but included a somewhat administrative boundary sentence.

**Conclusion: no clear general writing-quality gain over the old skill or no-skill baseline was established.** The revision deepens the reference library and broadens its coverage; this run does not prove that extra context produces better prose. It also does not establish a general regression: the sample is small and preferences include ties and disagreement.

No teaching content was tuned to these judgments and rerun against the same briefs. Future effectiveness claims require new briefs, repeated samples and preferably human judgments on actual writing. These artifacts remain evaluation material, not examples to retrieve during normal drafting.

## Inspect the evidence

- [Original prompts and scientific notes](prompts.json)
- [Anonymous candidate outputs](anonymous-outputs.json)
- [Condition mapping](condition-mapping.json)
- [No-skill output](no-skill.json), [old-skill output](old-skill.json), [revised-skill output](revised-skill.json)
- [First judge](judge-one.json), [second judge](judge-two.json)
- [Run configuration and snapshot digests](run.json)
- [Protocol](../protocol.md)
