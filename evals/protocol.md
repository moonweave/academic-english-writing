# Comparative writing evaluation

## Design

Choose held-out tasks matching the changed capability. The initial drafting comparison used a materials abstract, polymer Discussion and measured-circuit Results. A revision patch must also cover grammar-only correction, substantive paragraph revision, and minimal editing of already effective prose; drafting from notes cannot substitute for these tasks. Freeze prompts before generating the revised-skill outputs. Do not add those briefs or their target facts to the skill's teaching examples.

For a general effectiveness claim, compare no skill, pre-revision skill and revised skill in isolated writer contexts. A bounded patch may compare pre-patch and patched skills to check the changed behavior; state that this does not establish an advantage over no skill. Use the same supplied prompt and notes, the inherited model configuration, and one output per condition and case. Writers must not see the other outputs or evaluation judgments. Record source snapshots/commit identities, actual prompts and outputs. This is a small case study with no repeated sampling; do not infer statistical significance or broad model improvement.

Shuffle and relabel outputs separately for each case before an independent evaluator receives them. Give the evaluator the original request and notes, but no condition labels or preferred result. Reveal labels only after its assessment is complete. Condition blinding is limited: output style might reveal a condition even without its name.

## Assess independently

First identify factual errors, changed units/conditions, unsupported mechanisms/significance, specimen-to-population generalizations, and simulated-to-measured changes. A clear substantive factual error is a hard failure; it cannot be offset by elegant prose. Record omissions separately and consider the requested section and length rather than demanding that every note appear everywhere.

For revision, additionally check requested edit depth, preservation of effective voice/rhythm, unnecessary edits to sound prose, and whether editorial status notes intrude into the manuscript. A grammar-only output must not be rewarded for rewriting the argument. An unchanged correct passage can be the best result.

Then compare:

- **Coherence:** paragraph focus, sentence links, information order, evidence-to-interpretation progression.
- **Language:** idiomatic grammar/collocations, clear reference, appropriate rhythm and manageable dependencies.
- **Genre fit:** appropriate selection and emphasis for the requested Abstract, Discussion or Results.
- **Economy and voice:** informative wording, no generic hype or unnecessary caveat list, no formulaic repetition.

Use reasoned preferences and ties, not a decorative overall percentage. Mark a requested word-range miss and do not reward padding or invented content for meeting a minimum. Quote a short diagnostic excerpt from generated outputs when useful. Select a winner or tie for each case and explain it. Report the factual gate independently from stylistic preference.

## Interpretation

Accept the revision's structural and source-curation work only after validation; use comparative results to narrow claims about effectiveness. An isolated win is illustrative. Mixed results or ties must be reported as such, and any factual regression needs correction before claiming readiness. Do not tune the skill to an evaluator's preferred phrasing and rerun the same cases as if they remained held out. A later iteration needs fresh prompts or an explicitly labeled diagnostic rerun.

Historical self-review is in manual-review.md; it is not the independent comparison. The initial drafting run is under evals/comparison/. Store later runs separately (the revision patch uses evals/revision-comparison/) with their own prompts, anonymous outputs, mapping and assessment. Evaluation artifacts are not runtime references for drafting.
