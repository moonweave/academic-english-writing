# Electronics: eight operational patterns

Editorial analyses inspected 2026-10-23. Short quotations identify source wording; ellipses are not used to reconstruct long passages. Grammatical analyses and abstract schemata are editorial interpretations. Every application sentence below is an original invented teaching example, not a source finding or a reusable data claim. Choose a pattern because it serves the argument; do not insert every pattern or copy a source’s distinctive wording.

## E1 — source

Sebastian Pazos et al. (2025), “Synaptic and neural behaviours in a standard silicon transistor,” Nature 640, 69–76. [DOI/full text](https://www.nature.com/articles/s41586-025-08742-4). Named passages inspected in publisher text during initial curation; publisher access was intermittent on recheck.

### E1a: Attach the operating condition to the capability

**Locator:** abstract contribution sentences. **Source fragment:** “if biased in a specific (unconventional) manner”.

**How it works:** A conditional passive places the operating regime inside the capability assertion. The main clause can remain direct because the if-clause already bounds it. If changing the clause position, keep its referent and scope attached to the same component.

**Original application:** The oscillator generated a stable pulse train when operated at a 0.8 V supply.

**Limits:** Do not generalize to untested voltages, loads or temperatures. When reports a tested condition here; if can instead express a conditional capability.

### E1b: Describe the added component before its added function

**Locator:** abstract and Main final contribution paragraph. **Source fragment:** “By connecting one additional CMOS transistor in series”.

**How it works:** A by-gerund clause specifies the intervention and must share its actor with the main clause. Name the resulting structure before using a relative clause to give its function. Avoid a dangling modifier that makes the measurement perform the intervention.

**Original application:** By adding a feedback capacitor, we obtained a stage that maintained its output during the hold interval.

**Limits:** Only use the causal wording with evidence for the intervention. Component behavior does not establish total-system efficiency.

## E2 — source

Giacomo Indiveri et al. (2011), “Neuromorphic Silicon Neuron Circuits,” Frontiers in Neuroscience. [DOI/full text](https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2011.00073/full). Review; named passages inspected in publisher full text.

### E2a: Define function before detailing circuitry

**Locator:** Section 2 opening and Section 3.1 first description. **Source fragment:** “From the functional point of view”.

**How it works:** A framing adjunct announces the abstraction level. Parallel noun/relative-clause structures assign responsibilities; the implementation sentence then reuses the established block name. This limits unexplained switches between algorithm, block and transistor.

**Original application:** The receiver comprises an input stage that converts current to voltage and a filter that limits the signal bandwidth. The input stage uses resistive feedback.

**Limits:** Do not attach functions to the wrong block. A concise research paragraph may need only the relevant block, not the review article’s full taxonomy.

### E2b: Compare designs with a stable grammatical frame

**Locator:** Section 5, Table 2 discussion. **Source fragment:** “The specific choice of design style”.

**How it works:** A definite noun phrase refers to the preceding alternatives. Contrastive clauses compare the same dimensions in parallel, then make selection depend on application requirements. A preference becomes conditional rather than absolute.

**Original application:** The analog implementation used less power, whereas the digital implementation provided finer programmability. The choice depends on the required tuning range.

**Limits:** Keep process, workload and accounting comparable. A source’s discussion of design trade-offs cannot establish which option wins for a new application.

## E3 — source

C. E. Shannon (1948), “A Mathematical Theory of Communication,” Bell System Technical Journal 27, 379–423 and 623–656. [Part I DOI](https://doi.org/10.1002/j.1538-7305.1948.tb01338.x); [corrected reprint](https://people.math.harvard.edu/~ctm/home/text/others/shannon/entropy/entropy.pdf). Analysis concerns this reprint.

### E3a: Define a term and preserve it through the decomposition

**Locator:** Introduction, corrected reprint pp. 1–2. **Source fragment:** “It consists of essentially five parts”.

**How it works:** A definitional present-tense assertion is followed by parallel component definitions. Each term retains one meaning as the exposition moves from physical system to mathematical representation. Do not introduce synonyms for a defined object merely to vary prose.

**Original application:** The link comprises a transmitter, a channel and a receiver. The transmitter maps symbols to waveforms; the receiver estimates the transmitted symbols.

**Limits:** This is an original simplified example, not a quotation. State the actual system boundary and do not transfer model exclusions into unrelated applications.

### E3b: Give independent reasons for a representation

**Locator:** Introduction, corrected reprint p. 1. **Source fragment:** “The logarithmic measure is more convenient for various reasons”.

**How it works:** A choice statement precedes parallel reasons with distinct logical jobs. Keep practical motivation separate from mathematical consequences; do not make a list of near-synonymous importance claims. Use a proof where the argument requires one.

**Original application:** We report normalized error to compare devices of different gains. The normalization also makes the residuals dimensionless.

**Limits:** Only claim comparability when the normalization supports it. Explanation of a representation is not a derivation of its validity.

## E4 — source

Mirosław Firlej et al. (2023 preprint), “Ultra-low power 10-bit 50-90 MSps SAR ADCs in 65 nm CMOS for multi-channel ASICs.” [Versioned source](https://arxiv.org/abs/2312.14592v1); [PDF](https://arxiv.org/pdf/2312.14592v1). Printed page numbers exclude front matter. Only measurement passages selected; publisher-edition wording is not claimed.

### E4a: Name the independent variable and the fixed stimulus

**Locator:** Section 3.2, printed p. 9, Fig. 10 discussion. **Source fragment:** “as a function of the sampling frequency”.

**How it works:** A measured-quantity passive identifies the response, while as a function of names the sweep variable and an at-phrase fixes the stimulus. Subsequent sentences can report the trend without repeating an ambiguous “frequency.”

**Original application:** The amplifier gain was measured as a function of temperature at a fixed input frequency of 10 kHz. Gain decreased above 60 °C.

**Limits:** The numbers are invented. Distinguish sampling, input and clock frequencies and fixed absolute frequency from fixed fraction of Nyquist; do not silently exchange them.

### E4b: Make the power boundary visible before comparison

**Locator:** Section 3.3, printed p. 11, Fig. 12 discussion. **Source fragment:** “Contributions to the total power of key ADC blocks”.

**How it works:** A plural subject organizes component contributions; a following comparison identifies which contribution changes. Use the same denominator and circuit boundary before contrasting totals. A figure-reference present tense can accompany past-tense measurement conditions.

**Original application:** The analog and digital blocks consumed 0.30 and 0.12 mW, respectively. These values exclude the external bias circuit.

**Limits:** Do not copy this example’s exclusion into another design. State the actual inclusion boundary, rate and supply; matching units do not by themselves make power figures comparable.
