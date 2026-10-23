# Comparative writing evaluation

## Design

Use three held-out synthetic research briefs covering a materials abstract, polymer Discussion and measured-circuit Results. Freeze prompts before generating the revised-skill outputs. Do not add those briefs or their target facts to the skill's teaching examples.

Generate each brief in three isolated writer contexts: no skill, pre-revision skill, revised skill. Use the same supplied prompt and notes, the inherited model configuration, and one output per condition and case. Writers must not see the other outputs or evaluation judgments. Record source snapshots/commit identities, actual prompts and outputs. This is a small case study with no repeated sampling; do not infer statistical significance or broad model improvement.

Shuffle and relabel outputs separately for each case before an independent evaluator receives them. Give the evaluator the original request and notes, but no condition labels or preferred result. Reveal labels only after its assessment is complete. Condition blinding is limited: output style might reveal a condition even without its name.

## Assess independently

First identify factual errors, changed units/conditions, unsupported mechanisms/significance, specimen-to-population generalizations, and simulated-to-measured changes. A clear substantive factual error is a hard failure; it cannot be offset by elegant prose. Record omissions separately and consider the requested section and length rather than demanding that every note appear everywhere.

Then compare:

- **Coherence:** paragraph focus, sentence links, information order, evidence-to-interpretation progression.
- **Language:** idiomatic grammar/collocations, clear reference, appropriate rhythm and manageable dependencies.
- **Genre fit:** appropriate selection and emphasis for the requested Abstract, Discussion or Results.
- **Economy and voice:** informative wording, no generic hype or unnecessary caveat list, no formulaic repetition.

Use reasoned preferences and ties, not a decorative overall percentage. Mark a requested word-range miss and do not reward padding or invented content for meeting a minimum. Quote a short diagnostic excerpt from generated outputs when useful. Select a winner or tie for each case and explain it. Report the factual gate independently from stylistic preference.

## Interpretation

Accept the revision's structural and source-curation work only after validation; use comparative results to narrow claims about effectiveness. An isolated win is illustrative. Mixed results or ties must be reported as such, and any factual regression needs correction before claiming readiness. Do not tune the skill to an evaluator's preferred phrasing and rerun the same cases as if they remained held out. A later iteration needs fresh prompts or an explicitly labeled diagnostic rerun.

Historical self-review is in manual-review.md; it is not the independent comparison. The actual run's prompts, anonymous outputs, condition mapping and assessment belong under evals/comparison/ and remain evaluation artifacts, not runtime references for drafting.
