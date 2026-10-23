# Academic English Writing

A Codex skill for drafting and revising clear research prose in **materials science, polymers, and electronic engineering**.

It combines writing decisions, original worked examples, and **14 passage-level patterns from 7 research, review, and theory papers**. Patterns record what the sentence or paragraph accomplishes, how grammar supports that purpose, and when the pattern would overclaim.

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
- [Seven-paper pattern index](references/paper-patterns.md)
- [Why these papers, and why seven](references/selection-rationale.md)
- [Original worked examples](references/worked-examples.md)
- [Source-intake procedure](references/reference-intake.md)
- [Writing-guide provenance](references/sources.md)
- [Behavioral cases](references/smoke-cases.md) and [manual review](evals/manual-review.md)

The library selects useful passages, not papers declared universally excellent. Some entries model argument structure only. Source version, access scope, location, and transfer limits are recorded. Paper PDFs, unpublished manuscripts, and private research data are not distributed.

## Verification and limits

Skill frontmatter, local reference links, unfinished scaffolds, whitespace, and secret scanning are checked locally. Behavioral cases are reviewed by the authoring agent; this is not an independent or blinded quality evaluation. No CI workflow or cross-model benchmark is included in this initial release.

The seven-paper starting size reflects coverage and overlap judgments, not a measured optimum. RF/ADC measurement narratives and chemistry-specific synthesis prose remain opportunities for expansion. Actual author/journal preferences should guide subsequent curation.
