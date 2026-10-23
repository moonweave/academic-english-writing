# Academic English Writing

A Codex skill for drafting and revising clear research prose in **materials science, polymers, and electronic engineering**.

It combines writing decisions, original worked examples, and **19 operational patterns from 9 research, review, and theory papers**. Each pattern pairs a short source grammatical unit with a labeled editorial structure diagram and clause/tense/focus analysis, an original application on different content, and transfer limits.

This is an instruction and reference library, not a fine-tuned model. “Natural writing” means precise, coherent prose with a specific scientific argument. It does not mean detector evasion or decorative synonym replacement.

## Install

For a new Codex installation, clone the repository into your personal skills directory:

```sh
git clone https://github.com/moonweave/academic-english-writing.git ~/.codex/skills/academic-english-writing
```

If you configured a different `CODEX_HOME`, use its `skills/academic-english-writing` directory. If that location already contains a copy, inspect it before replacing anything. The repository root is the skill folder.

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
- [Nine-paper pattern index](references/paper-patterns.md)
- [Why these papers, and why nine](references/selection-rationale.md)
- [Original worked examples](references/worked-examples.md)
- [Source-intake procedure](references/reference-intake.md)
- [Writing-guide provenance](references/sources.md)
- [Behavioral cases](references/smoke-cases.md) and [historical self-review](evals/manual-review.md); [comparative protocol](evals/protocol.md)

The library selects useful passages, not papers declared universally excellent. Some entries model argument structure only. Source version, access scope, location, and transfer limits are recorded. Paper PDFs, unpublished manuscripts, and private research data are not distributed.

## Verification and limits

Skill frontmatter, local reference links, unfinished scaffolds, whitespace, and secret scanning are checked locally. The historical smoke cases were self-reviewed. A separate comparison uses isolated no-skill, old-skill and revised-skill writers with anonymous outputs and independent evaluators; see the [recorded results](evals/comparison/results.md). This run found no clear overall writing-quality gain; preferences were mixed. A separate [revision patch check](evals/revision-comparison/results.md) covers grammar-only correction, substantive revision and preservation of effective prose. Both versions passed all three cases with overall ties; the patched paragraph removed a redundant status clause. These are small case studies, not a cross-model benchmark. No CI workflow is configured.

The nine-paper library size reflects coverage and overlap judgments, not a measured optimum. The revision adds synthesis/characterization exposition, ordered thermal Methods and SAR ADC measurements; RF measurement writing and broader synthetic-procedure coverage remain opportunities for expansion. Actual author/journal preferences should guide subsequent curation.
