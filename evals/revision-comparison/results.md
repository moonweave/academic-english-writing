# Revision patch check

Date: 2026-10-23. New synthetic revision inputs were fixed before patching. Two isolated writers used the pre-patch and patched skills; two independent agent evaluators assessed anonymous A/B outputs. Condition labels were revealed after both completed. This is a bounded diagnostic check, not a new general writing-quality benchmark.

| Task | Required behavior | Judge one | Judge two |
| --- | --- | --- | --- |
| Grammar only | Correct agreement/reflexive forms; preserve the two-sentence structure and technical content | Both pass; tie | Both pass; tie |
| Substantive paragraph revision | Remove hype and administrative wording; calibrate the unsupported mechanism claim; retain observations and qualifications | Both pass; tie | Both pass; tie |
| Preserve effective prose | Retain the author's voice, rhythm and emphasis; leave sound text unchanged | Both pass; tie | Both pass; tie |

The grammar-only outputs were identical. The effective-prose outputs were identical to the input. In paragraph revision, both versions retained the scientific content and corrected the unsupported sole-mechanism claim. Both evaluators noted that only the pre-patch output retained a redundant clause announcing that the prospective control had not been performed; the patched output used a prospective modal without the status announcement. They treated that as a minor improvement and did not award an overall win.

No substantive factual or edit-scope failure was identified. These results confirm the requested behaviors in these cases; they do not establish that the patched skill outperforms the previous version or a no-skill baseline in general. The second case deliberately includes a known failure family, so removal of its status wording is diagnostic rather than a held-out generalization claim.

The evaluated snapshot differs from the published runtime only by a nonsemantic locator correction in one schematic, recorded with both digests in run.json. No rules or examples were tuned to these judgments and rerun against the same inputs. Exact model/sampling metadata were not captured. The earlier [drafting comparison](../comparison/results.md), which found no clear general improvement, remains unchanged.

Evidence: [requests and original inputs](prompts.json), [anonymous outputs](anonymous-outputs.json), [condition mapping](condition-mapping.json), [before](before.json), [after](after.json), [judge one](judge-one.json), [judge two](judge-two.json), [configuration and digests](run.json), [protocol](../protocol.md).
