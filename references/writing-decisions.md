# Writing decisions

These are editorial heuristics, not universal journal rules or measured findings about AI text. Examples are original teaching examples with invented data; never reuse their numbers as research evidence.

## Rhetorical work by section

| Context | Useful decision | Common failure |
| --- | --- | --- |
| Introduction | Narrow from a relevant problem to a specific unresolved question and explain why answering it matters. | A revolutionary-technology opening followed by an unsupported claim that no work exists. |
| Methods | Make the procedure reproducible; retain ordering, conditions, instruments, and definitions. | Removing operating conditions to shorten prose. |
| Results | State the measured comparison, conditions, and relevant figure before elaborate interpretation. | Replacing a result with “excellent performance.” |
| Discussion | Explain what observations support, examine alternatives where relevant, and delimit conclusions. | Turning a plausible interpretation into a uniquely proven mechanism. |
| Abstract | Select the question, approach, principal result, and supported contribution. | A miniature introduction with no concrete result. |
| Conclusion | State the answer and its demonstrated scope. | A new result, untested application, or expansive future-impact claim. |

Use the journal's structure; Results and Discussion may be combined. Do not force identical openings or endings across sections.

## Information and emphasis

Let a familiar object or question connect adjacent sentences. Introduce new information where it can receive appropriate emphasis. Keep the subject near its governing verb when intervening detail obscures the assertion. These choices follow Gopen and Swan; they are not fixed word-order laws.

Original example:

- Before: “A reduction in the resistance of the film was observed after annealing, which was significant.”
- After, if evidence establishes only a numerical change: “After annealing, the film resistance decreased from 12 to 8 kΩ.”
- Why: identifies the quantity and avoids inventing statistical significance. Resolve the original ambiguity from source evidence before using numerical values.

## Grammar decisions that can change meaning

- **Tense/aspect:** simple past commonly reports completed procedures and observations; present commonly states what a figure displays or an accepted relationship; present perfect links prior work to the current problem without a finished time anchor. These are defaults, not section-wide conversion rules.
- **Voice:** use active voice to clarify reasoning or agency; use passive voice when the sample, process, or measurement is the useful focus. Do not change focus just to enforce a preference.
- **Articles/countability:** introduce “a transistor,” then “the transistor” when identified. Check whether “current” means a quantity or several components. Do not mechanically add articles before material names or mass nouns.
- **Modifiers:** ensure a preparation clause modifies the prepared object: “After annealing, the films were characterized,” rather than implying the instrument was annealed.
- **Restrictive clauses:** distinguish a subset of devices from extra information about all devices; punctuation can change sample scope.
- **Comparisons/parallelism:** compare the same quantity with the same quantity. “The mobility exceeded that of the control” avoids comparing mobility with a device itself.
- **Prepositions:** retain what is varied and fixed: measured **at** a temperature, **under** illumination, **as a function of** gate voltage. Check collocations in accessible reference text when uncertain.
- **Connectors:** “because” asserts a reason; “therefore” asserts an inference; “whereas” compares clauses; “although” concedes a tension. A connector cannot supply a missing premise.
- **Quantities:** distinguish increased **by** 20% from increased **to** 20%, percentage points from percentages, and relative from absolute changes. Do not resolve “three times higher” numerically without its intended meaning.
- **Hedging:** state direct observations directly; qualify uncertain explanations locally. Avoid stacked hedges and indiscriminate weakening.

## Domain fidelity

| Domain | Preserve or clarify when relevant |
| --- | --- |
| Materials | Composition, phase, processing history, morphology, geometry, normalization, and the link actually established between structure and properties. |
| Polymers | Molar-mass definition and distribution, composition basis, conversion, cure history, strain/rate/frequency/temperature, thermal history, measured versus inferred network structure. |
| Devices | Bias and pulse conditions, geometry and normalization, hysteresis protocol, ambient, extraction method, device-to-device versus cycle-to-cycle variation. |
| Circuits/systems | Measured silicon versus simulation, process and supply, load and frequency, area definition, included peripherals, workload and precision, energy/power/latency boundaries. |

Apply only relevant items; not every detail belongs in every sentence. Endurance does not establish retention, material conductivity does not establish circuit speed, and a component metric does not establish system efficiency.

Original examples:

- “가교 밀도가 커져서 그런 것 같음. 팽윤만 측정함.” → “The reduced swelling is consistent with a higher crosslink density.” Do not claim crosslink density was directly measured or its cause established.
- A transistor response in simulation → “The simulated transistor exhibited…” Do not write “We experimentally demonstrated…”.
- Core power excluding peripherals → retain that boundary; do not describe it as total system power.
- Grammar-only: “The devices was measured at room temperature.” → “The devices were measured at room temperature.” Do not invent bias conditions or rewrite the argument.

## Revision scope and manuscript voice

For grammar-only correction, fix the actual grammar and preserve sentence organization, established terminology, numbers, citation anchors and scientific emphasis. For substantive revision, identify the point the paragraph is trying to establish, then change only the ordering or constructions that obstruct it. When prose already works, retaining it is a valid result; do not impose a preferred rhythm, voice or connector.

Evidence checks belong in the editing process. In the manuscript, connect a qualification to the inference it restricts. Do not turn every unperformed measurement into a sentence, but do not omit an explicit scientific limitation from a revision merely to sound confident. A shorter draft from notes may select relevant content according to genre; an edit of an existing manuscript must respect the requested retention scope.

Original teaching examples (no research evidence):

- Administrative: “These measurement boundaries delimit the reported amplifier metrics.” → Direct accounting, when supplied: “The reported power excludes the external bias circuit.” The second sentence tells the reader what the number includes.
- Status report: “The isotope experiment remains proposed work.” → Scientific role, when supplied: “Isotope labeling would distinguish the two pathways.” The modal already makes its prospective status clear; it must not imply that the experiment was performed.
- Disconnected caution: “There are limitations. The bonding mechanism is unknown.” → Local qualification: “The adhesion increase does not identify the bonding mechanism.” This preserves the uncertainty while stating which inference is unsupported.

These are decisions, not forbidden phrases. Retain explicit status wording when the deliverable is a review response, plan, progress report, or when the reader otherwise could mistake proposed work for a completed test. Do not add a negative comparison to prior work unless that comparison is relevant to the claim being made.
