# Academic English Writing

A Codex skill for drafting and revising clear research prose in **materials science, polymers, and electronic engineering**.

It combines writing decisions, original worked examples, and **19 operational patterns from 9 research, review, and theory papers**. Each pattern pairs a short source grammatical unit with a labeled editorial structure diagram and clause/tense/focus analysis, an original application on different content, and transfer limits.

This is an instruction and reference library, not a fine-tuned model. “Natural writing” means precise, coherent prose with a specific scientific argument. It does not mean detector evasion or decorative synonym replacement.

## Install

For a new Codex installation, clone the repository into your personal skills directory:

```sh
git clone https://github.com/moonweave/academic-english-writing.git ~/.agents/skills/academic-english-writing
```

This uses the current [Codex user skill directory](https://learn.chatgpt.com/docs/build-skills#where-codex-loads-local-skills). If that location already contains a copy, inspect it before replacing anything. The repository root is the skill folder.

## Use

```text
$academic-english-writing
이 문단을 자연스러운 학술 영어로 퇴고해줘.
수치, 실험 조건, 주장 강도는 유지하고 주요 변경 이유만 설명해줘.
```

```text
$academic-english-writing
Draft a Results paragraph from these observations. Distinguish measurements
from proposed explanations and retain all bias and pulse conditions.
```

```text
$academic-english-writing
이 논문의 Introduction과 Discussion에서 글쓰기 패턴을 분석해
참고 라이브러리에 추가해줘. DOI와 적용 조건을 기록해줘.
```

Grammar-only requests remain grammar-only. Missing experiments, numerical results, and citations are never supplied for fluency. New corpus entries are stored when requested, not whenever a paper is read.

## What's inside

- [Skill instructions](SKILL.md)
- [Writing and grammar decisions](references/writing-decisions.md)
- [Eleven-paper pattern index](references/paper-patterns.md)
- [Core/auxiliary selection and dated attention evidence](references/selection-rationale.md)
- [Original worked examples](references/worked-examples.md)
- [Source-intake procedure](references/reference-intake.md)
- [Writing-guide provenance](references/sources.md)
- [Behavioral cases](references/smoke-cases.md) and [historical self-review](evals/manual-review.md); [comparative protocol](evals/protocol.md)

Eight core papers provide fourteen patterns; three auxiliary papers provide seven. Core selection combines documented influence or institutional attention with a separate editorial prose assessment. Two new core papers are abstract-only exemplars. The library selects useful passages, not papers declared universally excellent. Some entries model argument structure only. Source version, access scope, location, and transfer limits are recorded. Paper PDFs, unpublished manuscripts, and private research data are not distributed.

## Verification and limits

Skill frontmatter, local reference links, unfinished scaffolds, whitespace, and secret scanning are checked locally. The historical smoke cases were self-reviewed. A separate comparison uses isolated no-skill, old-skill and revised-skill writers with anonymous outputs and independent evaluators; see the [recorded results](evals/comparison/results.md). This run found no clear overall writing-quality gain; preferences were mixed. A separate [revision patch check](evals/revision-comparison/results.md) covers grammar-only correction, substantive revision and preservation of effective prose. Both versions passed all three cases with overall ties; the patched paragraph removed a redundant status clause. These are small case studies, not a cross-model benchmark. No CI workflow is configured.

The eleven-paper size reflects coverage and overlap judgments, not a measured optimum. See the [selection record](references/selection-rationale.md) and [dated Crossref snapshot](references/attention-snapshot.json). Research attention does not prove good writing, and these curator selections await the user's style preferences. RF measurement writing, broader synthetic-procedure coverage and current 2026 highlights remain gaps. The [curation patch smoke check](evals/curation-smoke.md) records structural, source and two-request behavioral checks; the older writing comparisons do not evaluate these two new abstract patterns.
