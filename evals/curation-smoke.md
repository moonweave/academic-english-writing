# Curation patch smoke check

Date: 2026-10-23. One separate agent, two requests, read-only. This was not blinded: the agent inherited session context. No claim of independent corpus ranking or writing superiority follows.

Tested runtime/reference snapshot SHA-256: `89f83f82cf03feae59c9a19727bf8c688290f5576aad1258b6a3d85226564e82`. Computed over SKILL.md followed by sorted references/*, hashing each relative path, NUL, file bytes, NUL. README and this report are outside that digest.

## Request 1: explain the corpus to a prospective user

The agent was asked whether the skill contains celebrated, well-written papers and to explain representatives and inspection scope for materials, polymers and electronics.

Observed answer: identified 11 papers / 21 patterns and 8 core / 3 auxiliary sources; distinguished a reference library from model training. It used Sun 2012, Guerre 2020 and Pazos 2025 as domain representatives, labeled Zhao 2024 and Cheng 2024 abstract-only, and separated dated research-attention evidence from passage-level editorial quality judgments. It did not claim exhaustive 2026 coverage or universal best-writing status.

Result: selection and access labels were communicated accurately in this request.

## Request 2: draft from limited membrane observations

Input: membrane kept its shape at 25 °C in water for 24 h; higher temperatures and salt were not tested. Requested two sentences using relevant guidance when helpful.

Actual output:

> The membrane retained its shape in water at 25 °C for 24 h. Its shape retention at higher temperatures or in the presence of salt was not evaluated.

Result: retained all supplied conditions, did not import P4a's invented threshold or unsupported unless claim, and did not infer salt stability. The qualification was explicitly part of the test input.

## Limits and other checks

One agent and one output per request provide only a small behavioral smoke signal. The two new abstract patterns have not received a comparative writing benchmark. Earlier comparison results remain historical and unchanged. Frontmatter validation, local reference links, pattern/metadata consistency, whitespace checks and gitleaks were checked separately; no GitHub Actions workflow is configured.
