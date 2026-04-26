# Source-grounding summary

Written 2026-04-26 after a source-grounding pass through Santana 2016, HPC book chapters 4 / 7 / 8 / 16 + Predictions appendix, and a verification pass on Casten et al. 2026. This file is the bridge between source-grounding and drafting. The per-cluster template, §2, and §9 all draw from here.

## What the paper inherits from Santana 2016 (Ergo 3.19, DOI 10.3998/ergo.12405314.0003.019)

### Three criteria for any candidate ontology of `language` X (Santana §2)

1. X exists, in a form accessible to scientific study.
2. X is (descriptively) a primary object of study for linguists.
3. X is reasonably referred to as `language`.

Santana proposes these as the implicit shared criteria invoked by all sides in ontology-of-language debates. He accepts the methodological-naturalist premise (deeds, not words, determine whether X satisfies (2)) and adds a heuristic: if X is the common link between otherwise disparate objects of study, it's a good candidate for primary object of study.

### Three ontologies, all legitimate (Santana §§3-5)

1. **Psychological** (Chomsky's i-language; psycholinguistics generally; Hauser-Chomsky-Fitch's FLN/FLB).
2. **Social** (Labov, sociolinguistics; Lewis 1969 on convention; Wiggins 1997; Devitt 2003, 2008; Kripke / Putnam / Burge externalism; Grice / Stalnaker / Tomasello on multi-agent pragmatics).
3. **Abstract** (Katz Platonism; Frege, Montague; Carnap-style methodological idealization; structuralism as candidate formalism; NLP / extensional adequacy as the abstract ontology's working niche).

Santana's strategy: accept the positive arguments for each ontology; reject the negative arguments that would eliminate the others. Chomsky's three critiques of E-language (folk-concept conflation, anti-mechanism idealization, uselessness given i-language) are rebutted in turn. Davidson's "no such thing as a language" puzzle is reframed as a scientific question about how communities of communicating speakers are maintained. Rey's intentional inexistents and Heck's explanatory-priority arguments fail similarly.

### Two strictures on pluralism (Santana §7)

1. **No isolationism.** "Sophisticated pluralism treats linguistics as a unified field characterized by multiple primary objects of study, not as three isolated fields with their own independent subject matters." Research on one ontology has indirect significance for the others; questions about how the three relate are themselves important.
2. **No agnosticism.** Three reasons:
   - Some debates are intractable unless subject matter is clear (Partee 1979 on Millianism vs descriptivism).
   - Idealizations licensed depend on subject matter.
   - Confirmation requires knowing what evidence is evidence for.

### Where this paper agrees with Santana (load-bearing, must be acknowledged)

- Pluralism is right. The label `language` does pick out distinct things; positive arguments succeed and negative arguments generally fail.
- The two strictures are correct and load-bearing. The paper inherits them.
- The three Santana ontologies cover real ground; they map (roughly) onto our six-cluster taxonomy as follows:
  - Psychological → Capacity + Idiolect / I-language
  - Social → Population-level convention + Named sociohistorical object + parts of Communicative practice
  - Abstract → Abstract formal system

### Where this paper extends Santana

1. **Granularity.** Santana's three classes are too coarse for the cross-disciplinary work. The social ontology alone contains at least three distinct projection-targets (Lewis-Labov convention; Haugen / Silverstein / Agha / Bourdieu on institutional named-language objects; Hymes / Goffman / Searle on communicative practice). The paper's six-cluster taxonomy is a finer partition that tracks differences working scientists already treat as different, and that license different inferences.

2. **Realist-discipline machinery.** Santana states the criteria (existence, primacy, reasonable use) and the strictures (no isolationism, no agnosticism), but supplies no machinery for diagnosing realist standing within a cluster, no diagnostic for slippage between clusters, no defeat conditions for projection. HPC supplies all three. **This is the paper's contribution.**

3. **Slippage as diagnosable failure mode.** Santana's no-agnosticism stricture motivates the diagnosis but doesn't supply the diagnostic. HPC adds: if cluster A and cluster B share a label, and someone reads evidence about A as evidence about B, the slippage is diagnosable in HPC terms — does B's stabilizers support the inference at the relevant grain? Are the cohorts and operationalisations the same?

### Attribution discipline (mandatory)

Pluralism about the ontology of `language` is Santana's. Projectibility-for-a-purpose is Boyd's. The paper's contribution is the synthesis: HPC discipline applied to a more granular cluster taxonomy than Santana's three ontologies, plus slippage diagnoses as the methodological payoff. The paper must not present pluralism or projectibility as its innovation. (CLAUDE.md, attribution discipline.)

## What the paper inherits from the HPC book

### The maintenance view (Chapter 4)

**HPC commitment:** "A category counts as real, for the purposes at hand, when (a) it is associated with a robust cluster of properties, and (b) there exist processes that tend to produce and stabilize that cluster across the relevant range of contexts, yielding projectible generalisations."

- **Stasis** = standing, position; **homeo** = same / similar (Boyd's term unpacked).
- **Spinning top**, not ball-at-bottom-of-valley: dynamic stability resists perturbation; stop the spin and the cluster falls.
- **Mechanism** = empirically tractable process with a characteristic perturbation signature. **Stabilizer** = the functional role a process plays in maintaining clustering. (Mechanism is causal; stabilizer is functional.)
- **Meta-Occam:** parsimony at the mechanism level, not the category level. Few stabilizer types; many cluster types.
- **Copied kinds (Millikan), etiological kinds (Khalidi), unicepts (Millikan):** categories whose members are produced from each other or from a common template; identified through multiple fallible diagnostics, none privileged as definitional.

### The slogan (Chapter 7)

**A linguistic category is a profile of co-occurring properties, stabilized by mechanisms, projectible relative to purposes.**

Three-part architecture:
1. **Profile** — visible pattern of co-occurring properties.
2. **Stabilized by mechanisms** — acquisition, entrenchment, alignment, functional pressure, transmission keep properties travelling together.
3. **Projectible relative to purposes** — the payoff: induction-licensing, but only for questions the mechanisms underwrite.

**A profile that doesn't support inference is a cluster but not a category — it's a "filing label."** Mechanism is metaphysics; projectibility is epistemology.

### Field-relative projectibility (Chapter 7)

A "field" is the local explanatory matrix relevant to the inference at hand — sometimes a subfield (syntax / semantics), sometimes a conditioned slice (dialect, register, discourse community).

**Boyd 1999 is the source.** The same extension can support different projectible categories for different analytical purposes — not perspectivalism (different views of one thing) but distinct HPCs that happen to overlap in extension, each maintained by its own mechanism set, each projectible in its own field.

Worked examples in the book:
- **Tomato** = botanical fruit (reproductive biology) vs culinary vegetable (flavour chemistry, kitchen practice).
- **Proper noun** (syntactic distribution: heads NP, fills argument slot, triggers agreement) vs **proper name** (semantic: rigid reference, referential opacity, individual-tracking).
- **Constituency** (groups, displacement, coordination) vs **dependency** (governance, extraction, locality, attachment costs).
- **Why colour doesn't grammaticalize:** colour is salient and projects for ecological purposes (edibility, danger, health), but predicts only object-relative things; animacy projects relationally. So colour grammaticalizes nowhere; animacy grammaticalizes widely.

**Field-relative projectibility is what licenses our six-cluster taxonomy.** Each cluster is projectible for its field. Slippages between clusters are claims about one cluster's projection target read off another cluster's evidence.

### The three checks (Chapter 7) — for §2 and the per-cluster template

1. **Cluster check.** Does property covariance hold across samples and contexts?
2. **Homeostasis check.** Are there identifiable perturbations under which the cluster reconstitutes?
3. **Projectibility check.** Are there counterfactual-supporting inferences in new contexts?

These checks can yield different answers for different fields. That's the framework working, not failing.

### Three uses of "mechanism" — for §9 slippage

- **Maintenance mechanisms.** Population-level (acquisition, entrenchment, alignment, transmission).
- **Speaker mechanisms.** What an individual invokes during production / comprehension.
- **Analyst diagnostics.** Criteria a linguist uses to identify the cluster (semantic tests, distributional paradigms, agreement tables).

**Conflating these levels is how working theories slide toward circularity** — treating an analyst diagnostic as a speaker representation, or a speaker representation as a maintainer mechanism. **Important slippage class for §9:** the operationalisation slippages catalogued there ("the corpus IS the language", "competence IS the language", "the treebank IS the language") are exactly conflations of analyst diagnostics with maintenance mechanisms.

### The two diagnostics + three failure modes (Chapter 8)

**Two diagnostics for strict HPC status:**
- **Projectibility diagnostic.** Train on one dataset, test on held-out. Does it transfer?
- **Homeostasis diagnostic.** Can we name the stabilizers? Does the cluster fray under targeted perturbation?

**Three failure modes:**
- **Thin** — fails homeostasis. The pattern is there but no stabilizer maintains it (preposition copying / pruning; *cromulent* outside Simpsons-fan communities). Smoke ring, not category.
- **Fat** — fails projectibility. The label lumps mechanistically distinct subgroups (traditional `adverb`: manner / degree / sentence adverbs are different braids). Wastebasket, not category.
- **Negative** — fails both. Defined by absence (`non-finite clause`, Left Branch Condition).

**Critical confound:** projectible-but-not-homeostatic = corpus artifact. Annotation pipelines, register selection, editorial norms can produce stable cross-corpus patterns whose maintenance is convention, not mechanism. **This is one of the operationalisation slippages.** Annotation-driven projectibility is a slippage risk, not evidence of cluster reality.

### The HPC-kind audit template (Chapter 8) — basis for the per-cluster template

For any candidate category C:

1. **Target + scope.** What entities/events does C range over? Specify population/register, time slice, grain (tokens/constructions/categories/meta-categories).
2. **Property cluster (profile).** 6-10 candidate properties (distributional, morphosyntactic, semantic/pragmatic, processing, acquisitional, diachronic, sociolinguistic); central vs peripheral; which covary robustly.
3. **Homeostatic stabilizers.** Acquisition, entrenchment/use, interactive alignment, iterated transmission, institutional enforcement; what each predicts about persistence/repair under perturbation.
4. **Projectibility claims.** What inductive bets does C license, for which tasks/data types? Intended domain of stability and generalisation.
5. **Boundary behaviour.** Expected borderline cases and decouplings, with stabilizer-based explanations.
6. **Failure-mode gate.** Thin / fat / negative.
7. **Falsifiers / stress tests.** What pattern would force reclassification? What perturbation should reveal decoupling?

**The per-cluster template (PLAN.md) maps onto this:** paradigm cases ↔ profile + boundary behaviour; diagnostics ↔ analyst tests applied; stabilizers ↔ stabilizers, at the right grain (micro/meso/macro); projection target ↔ projectibility claims (conditional form: "observed P licenses expected Q in unobserved cases"); defeat conditions ↔ falsifiers; slippage risks ↔ which other clusters this one gets confused with.

### The grain question and Madagascar fallacy (Chapter 8)

"The fauna of Madagascar" is stable, distinct, has a causal history — but isn't itself a species. It's an ecosystem of species. **Language is an ecosystem.** The HPCs are the components — constructions, lexemes, phoneme contrasts, sometimes families or paradigms — *not* the grammar as a whole, and certainly not `English` or `language` itself.

**Implication for the paper.** The umbrella label `language` is not itself an HPC. It's a coordinative label spanning an ecosystem of clusters. Some of the six clusters are themselves HPC candidates (Capacity in some sub-axes, Idiolect, parts of Communicative practice). Others are clearly more ecosystem-like (Named sociohistorical object, Population-level convention, Abstract formal system as analyst-construct). The per-cluster template should make the grain explicit.

### Coupling typology (Chapter 8) — for the per-cluster template's grain section

- **Hard coupling.** Form, contrastive identity, inferential habit are locked together (phonemes). Stabilizers: physical, perceptual, social.
- **Loose coupling.** Form and meaning come apart. Bidirectional inference between two poles, maintained by entrenchment, alignment, transmission. **Most "interesting linguistic action" lives here.** Fat classes arise here when analysts treat loosely-coupled subclusters as one unit.
- **Composite coupling.** Constructions. Form-value pairings stabilized by use. Stabilizers: cue redundancy, frequency entrenchment, normative pressure.

### Four levels of bearer (Chapter 8) — for the per-cluster template's stabilizer-grain section

1. **Individual** — speaker's conditional disposition.
2. **Population** — distribution of dispositions across speakers, networks, time.
3. **Conditioning variables** — dialect, register, discourse community (parameters of the generative mixture).
4. **Institutional loops** — schooling, exams, style guides, tagsets, parsers, editorial policies, platform norms.

**Each cluster sits across some subset of these levels.** Capacity: 1 (and biologically deeper). Idiolect: 1. Population-level convention: 2. Named sociohistorical object: 3 + 4. Communicative practice: 1, 2, 3. Abstract formal system: outside this — analyst-constructed.

### Social stabilization (Chapter 16) — for Population-convention and Named-sociohistorical-object clusters

**Core methodological commitment:** "No conditioning gain, no maintenance claim." If you claim a cluster is real and maintained, conditioning on the relevant variables (dialect, register, discourse community) should improve projectibility. If it doesn't, the maintenance story is unsupported.

**The mixed-bin problem.** Pooled data conflates conditioned systems. "One pooled curve isn't one grammar." The unconditioned probability is the messy sum; the conditioned probability is the tight coupling. Mechanisms are most clearly visible at the conditioned level.

**Two dimensions of conditioning:**
- **Dialect** = variety according to user (durable, speaker-linked).
- **Register** = variety according to use (situational, interaction-linked).
- Where both converge → **discourse community** with institutional gatekeeping as additional stabilizer.

These are attractor basins in continuous space, not discrete types.

**Acquisition as source inference.** Children acquire situation-specific patterns first (Wiese 2023's com-sits), only later abstract to named-language labels. Source inference is operative from days after birth (Mehler et al. 1988, Kinzler et al. 2007 on accent over race in friendship choices).

**Indexicality as the inverse function of grammar.** Hear a form, infer a source. Eckert 2008's indexical field is an ideologically structured space of potential social meanings. Source attribution can stabilize categories — and can also stabilize the erasure of persons behind types (Cavell on knowing vs acknowledging).

**Looping kinds (Hacking 1999).** Classifications loop back to shape behaviour they describe. Speakers learn that a form is "incorrect" or "formal" and adjust → adjustment reinforces the category. Particularly relevant for Named-sociohistorical-object cluster.

**Two payoff dimensions in the social stabilization game:** communicative clarity rewards convergence; identity management rewards divergence. Code-switching, style-shifting, register-mixing are the predicted stress points where the two pull apart.

### Predictions appendix — for the per-cluster template's defeat conditions

Most relevant predictions (each is defeasible and applies to any maintained category):

- **P1: Asymmetric fraying.** When stabilizers weaken, tight diagnostics erode before loose ones. Decay is patterned, not uniform.
- **P5: Conditioning recovers structure.** Apparent gradience decomposes under social conditioning. **If conditioning produces no gain, the maintenance claim is unsupported.**
- **P8: Developmental cluster tightening.** Children's diagnostics become more correlated over time, not just more accurate.
- **P9: Category comorbidity.** Categories sharing mechanisms co-occur typologically more often than chance.
- **P10: Hub-node asymmetry.** One property's removal destabilizes the cluster more than others.

**Two global defeat conditions for HPC theory itself:**
- **D1: Projection without maintenance.** A robust, cross-linguistically stable category that projects strongly with no identifiable causal structure sustaining the cluster.
- **D2: Structure without lift.** Usage variation that proves to be a random walk with no recoverable structure under proper statistical control.

(Per-cluster defeat conditions in the paper should be more specific — what would falsify the maintenance claim *for this cluster*.)

## What the paper adds (synthesis)

1. **A more granular cluster taxonomy than Santana's three ontologies.** Six clusters at uneven grain, each with its own projection target, stabilizers, and defeat conditions. Animal communication and programming languages handled as boundary cases under Capacity and Communicative practice. Language of thought set aside in §2 as a metaphorical extension that doesn't share the projectibility profile of public-object senses. Methodological-construct sense redistributed to the slippage section as operationalisation slippage.

2. **HPC discipline as the methodological backbone Santana's pluralism lacks.** Each cluster is evaluated against the three checks (cluster / homeostasis / projectibility) and the two strict diagnostics (projectibility / homeostasis). Stabilizers are specified at appropriate grain (individual / population / conditioning / institutional). Projection targets are stated in conditional form: "observed P licenses expected Q in unobserved cases; defeated if D."

3. **Slippage as a diagnosable failure mode.** §9 catalogues the recurrent patterns:
   - **Cross-cluster slippage** — evidence about A read as evidence about B because they share the label *language* (Capacity → Faculty, Capacity → Abstract-formal-system, Communicative-practice → Idiolect, Named-sociohistorical-object → Population-convention, etc.).
   - **Within-cluster sub-axis slippage** — Casten / Pinker is the worked example: HAQER + verbal-performance phenotype evidence (a Capacity sub-axis: developmental-acquisition-performance) read as evidence about a different Capacity sub-axis (faculty / processing-architecture). Whether this counts as within-cluster or cross-cluster (Capacity → Abstract formal system) is a framing decision for §9.
   - **Operationalisation slippage** — analyst diagnostic conflated with maintenance mechanism. "The corpus IS the language" / "competence IS the language" / "the treebank IS the language" / "the LLM output IS the language." Distinct slippage class because it conflates the three uses of "mechanism" rather than two clusters.
   - **Grain slippage** — claim made at one grain treated as a claim at another. "English does X" treated as a Capacity claim, an Idiolect claim, a Population-convention claim, or a Named-sociohistorical-object claim, with the four supporting different inferences.
   - **Convention-driven projectibility slippage** — annotation/register/genre-driven cross-corpus consistency mistaken for mechanism-driven cluster reality. The corpus-artifact failure mode from Chapter 8.

4. **The umbrella as coordinative label, not realist kind.** Per the Madagascar fallacy. `Language` is the ecosystem; the six clusters are some of its species; new clusters are admissible if they pass the projectibility and homeostasis tests.

## The §1 hook: Casten / Pinker, source-grounded

### Source

Casten, L. G., et al. (2026). Ancient regulatory evolution shapes individual language abilities in present-day humans. *Science Advances*. DOI 10.1126/sciadv.aed5260. Published 22 April 2026.

### Verified quantitative claims (cross-checked against the paper)

- HAQERs comprise less than 0.1% of the human genome.
- Discovery N = 350 in EpiSLI cohort; total replication N > 100,000.
- HAQER CP-PGS shows β = 0.18 on F1 (sentence repetition) in EpiSLI (P = 1.2 × 10⁻⁴, FDR-adjusted P = 0.004).
- HAQER CP-PGS shows no association with nonverbal IQ (F3, β = 0.06, P = 0.19, FDR-adjusted P = 0.61).
- Average HAQER SNP carries 188× more predictive power for language than other SNPs.
- Cross-species comparison: 49 vocal-learning mammals + 121 non-vocal-learner species among 170 nonprimate mammalian species analysed.
- Archaic genome N = 10 (8 Neanderthals, 2 Denisovans).
- Replication cohorts: SPARK (autism-enriched, P = 7.9 × 10⁻⁵), ABCD (verbal-learning, P = 0.048), UK Biobank (P = 0.002).
- Balancing selection: HAQER polygenic scores stable over ~20,000 years.

### What the paper measures vs what the reception claims

The paper measures (1) regulatory polygenic signal in HAQERs and (2) F1, primarily driven by sentence repetition (a developmental verbal-performance phenotype). It gestures at (3) cross-mammalian vocal-learning toolkit. The popular reception (Pinker tweet, 2026-04-25, citing Pinker & Bloom 1990) reads it as evidence for (4) the modular language faculty (Pinker-Bloom Chomskyan grammatical capacity).

The slippage: HAQER + F1 evidence is about a developmental verbal-performance capacity (Capacity cluster, acquisition-and-performance sub-axis) — closer to clinical and developmental prediction than to faculty-architecture claims. The Pinker reception conflates this with the language-faculty / processing-architecture sub-axis (or arguably with the Abstract formal system cluster's claims about hierarchical structure-building).

The §9 framing decision: is this within-cluster (Capacity acquisition-and-performance → Capacity faculty-and-processing) or cross-cluster (Capacity → Abstract formal system)? The intake note (`notes/casten-2026-haqer-slippage-example.md`) leans within-cluster. Decide when drafting §9.

### Methodological caveats to carry into the prose if cited

- F1 construct is broader than "language" (sentence repetition draws on morphosyntax, phonology, working memory, attention, lexical knowledge, task compliance).
- Replications phenotypically coarser than discovery (SPARK, ABCD, UK Biobank don't use the EpiSLI battery).
- CP-PGS weights derived from a cognitive-performance GWAS entangled with education, cognition, and SES before HAQER stratification (UK Biobank follow-up uses word-reading PGS as partial corrective).
- Archaic-genome N = 10 underwrites the popular "Neanderthals had language" framing, which is much weaker than the press version implies.

These caveats matter less for the paper's use of the case (which depends on *what was measured*, not magnitude of effect) than they would for any empirical use, but they're worth flagging for prose honesty.

## Bib status

- ✅ Santana 2016: in `references-local.bib` as `santana2016language`.
- ✅ Boyd 1989, 1991, 1999: in central bib (and additional Boyd entries: 1979, 1990, 2012).
- ✅ Khalidi 2013, 2015 three: in central bib.
- ❓ Casten et al. 2026: not yet in either local or central. Add to `references-local.bib` when §1 is drafted.

## Capacity cluster sub-axes (HCF 2002, PJ 2005, FHC 2005, JP 2005, source-grounded 2026-04-26)

The HCF / PJ / FHC / JP exchange is itself a worked example of cluster-distinction work. HCF tried to distinguish FLB from FLN; PJ argued the recursion-only Hypothesis 3 was too narrow; FHC clarified that PJ blurred the FLB/FLN distinction; JP added that FHC's "current utility / functional origin" dichotomy omitted current adaptation. Each move is a sub-axis of the Capacity cluster being foregrounded.

### HCF 2002's distinction

- **FLB (Faculty of Language, Broad sense):** internal computational system (FLN) + sensory-motor system + conceptual-intentional system + interfaces. Excludes other organism-internal systems (memory, respiration, circulation) that are necessary but not sufficient for language.
- **FLN (Faculty of Language, Narrow sense):** "The abstract linguistic computational system alone, independent of the other systems with which it interacts and interfaces." Some subset of the mechanisms underlying FLB.
- **Hypothesis 3 (provisional):** FLN comprises only the core computational mechanisms of recursion as they appear in narrow syntax and the mappings to the interfaces. FLN is uniquely human; most or all of FLB is shared with nonhuman animals.
- **Comparative-biology methodology:** distinguish homology (descent) from analogy (independent evolution); use animal data to test what's shared vs unique. Cited example: Fitch & Hauser 2004 cotton-top tamarin AnBn study — tamarins fail to acquire the recursive grammar but master the finite-state variant.
- **FLN may have evolved for reasons other than language.** "Comparative studies might look for evidence of such computations outside of the domain of communication (for example, number, navigation, and social relations)."

### PJ 2005's critique (recursion-only hard to sustain)

- **Conceptual structure:** PJ concur with HCF that human conceptual structure overlaps with primates with some uniquely human additions (ToM, intuitive physics, ownership, multi-part tools, deontic concepts). Some concepts (week, advanced numbers) are only acquirable with language.
- **Speech perception:** PJ contest HCF's null hypothesis that no evolutionary changes occurred. Evidence: phenomenologically distinct (sound vs speech), brain-area dissociations (pure word deafness, amusia), early infant preference for speech (already at neonate stage), primate-human differences in formant transitions.
- **Speech production:** descended larynx in adult women + children + infants > 3 months; spinal-cord enlargement for breathing control; cortical control over articulation; vocal babbling. "Capacity for vocal imitation" is really "capacity to learn to produce speech" (humans aren't generally good at vocal imitation, only at speech sounds and melodies).
- **Phonology** (HCF made no mention): combinatorial structure with discrete infinity but **not technically recursive** (syllables can't embed in syllables). Language-specific (analogues in birdsong / cetacean song but not primates). Rule-governed adjustments serve "parity" requirement (Liberman & Mattingly 1989, Slobin 1977). Major counterexample to recursion-only.
- **Words:** 50,000-word lexicon; range and precision of concepts; learnability; bidirectional Saussurean signs; meaning defined by relations to other words. HCF's deflection (word learning is domain-general ToM) fails: words encode syntactic category, argument structure, selection restrictions; functional morphemes are continuous with syntax.
- **Syntax beyond recursion:** four combinatorial devices — hierarchical phrase grouping (the recursive component HCF refer to), word/phrase ordering, agreement, case-marking. Languages vary in reliance (English: order + constituency; Warlpiri: case + agreement freely; German: balanced). Pirahã (per Everett 2004) reportedly lacks recursion but has phonology, morphology, syntax.
- **Genetic evidence (FOXP2 etc.) is incompatible with recursion-only:** SLI sufferers have deficits across domains of grammar, not just recursion.
- **Critique of Minimalist Program** as the source of the recursion-only hypothesis: MP "chooses to ignore" most of phonology, derivational/inflectional morphology, basic phrase structures, word order phenomena, lexical-entry source, grammar-processing connection, grammar-acquisition connection. PJ argue MP should not be taken as carrying out a mandate to support claims about language evolution.
- **PJ's positive thesis:** language is an adaptation for the communication of knowledge and intentions; evolved piecemeal; multiple signs of partial specialization; not a "perfect" / non-redundant / unsuited-for-communication / designed-for-beauty system.

### FHC 2005's reply (clarifications)

- **PJ blurred the FLB/FLN distinction.** Hypothesis 3 concerns ONLY FLN, not "language" as a whole. Many of PJ's arguments are irrelevant to that hypothesis.
- **HCF acknowledge the two senses of "language":** for many linguists, "language" delineates an abstract core of computational operations; for many biologists/psychologists, it means "the communication system used by human beings." Neither is more correct, but statements about one may be inapplicable to the other. The FLB/FLN distinction is meant to keep these separate. **This is itself a cluster-distinction move that aligns directly with our paper's thesis.**
- **PJ's emphasis on past adaptive history is misplaced** because such questions are unlikely to be resolved empirically given lack of data — adaptive storytelling vs research.
- **Logical error:** offering an adaptive hypothesis as an alternative to a mechanism hypothesis. Function and mechanism are independent questions.

### JP 2005's surreply

- **Three-way distinction in evolutionary explanation, not two:** current utility (use at present), functional origins (what trait was adapted to in first organisms), and current adaptation (what trait was selected for in species being considered). FHC's framework excludes current adaptation, which JP claim is the most biologically interesting question.
- **FHC slice adaptive functions too finely.** At a more generic level, we know what bat echolocation is FOR (sensing in the dark) even if we can't say whether it evolved for navigation vs prey-finding.
- **Selective pointlessness:** FHC say all adaptive hypotheses are pointless, but Hauser and Fitch's own experimental work tests adaptive function. And FHC themselves say FLB shows "signs of adaptive design" shaped by communication.
- **Reverse-engineering / functional analysis** as additional source of evidence FHC ignore. Goodness-of-fit between design specs and observed properties.
- **Recursion is found in visual cognition** — Pinker-Bloom argument; recursion is not unique to language.

### Capacity-cluster sub-axes for the per-cluster template

The exchange surfaces at least five sub-axes of the Capacity cluster, each with different stabilizers and projection targets:

1. **Capacity-as-faculty / processing-architecture (FLN sub-axis).** What's uniquely human and uniquely linguistic in the abstract computational system. HCF: recursion + interfaces. PJ: more (phonology, words, agreement, case). Stabilizers: contested (innate genetic endowment per classical Chomskyan view; cognitive architecture more broadly per PJ). Projection target: structural acquisition predictions, cross-linguistic universals.

2. **Capacity-as-broad-faculty (FLB sub-axis).** Sensory-motor + conceptual-intentional + FLN + interfaces. Stabilizers: largely shared with other species (vocal-tract anatomy, theory of mind, conceptual representations, vocal imitation). Projection target: comparative cognition, neurophysiology of action-perception systems.

3. **Capacity-as-developmental-acquisition.** Children acquire language at species-specific rates and modes. Sensitive period (analogues in birdsong). Babbling. Phonology, vocabulary, syntax acquisition. **Casten et al.'s F1 (sentence repetition) sits here** — about individual differences in developmental verbal performance. Stabilizers: developmental input, neural and cognitive architecture, modality-general abstraction. Projection target: developmental and clinical prediction.

4. **Capacity-as-comparative-biology / vocal-learning.** Cross-mammalian convergence. Vocal-learning species (songbirds, dolphins, parrots). Casten et al.'s cross-mammalian regulatory convergence (49 vocal-learning mammals, HAQER-like sequences). Stabilizers: regulatory tuning of prenatal expression, transcription factor binding, chromatin accessibility patterns. Projection target: cross-species comparison, developmental neurogenetics.

5. **Capacity-as-impairment-phenotype.** SLI, FOXP2 disorders, dyslexia, stuttering. Genetic evidence (PJ 2005's appeal to FOXP2 against recursion-only). Stabilizers: specific genetic loci, neural-substrate variations. Projection target: clinical prediction, genetic-architecture inference.

The §1 slippage (Casten/Pinker) traverses sub-axes 3 and 4 (what Casten et al. measure) → sub-axis 1 (what Pinker reads it as). This is **within-cluster sub-axis slippage**. Whether it also counts as cross-cluster slippage to Abstract formal system depends on how the "language faculty" claim is parsed.

The HCF / PJ exchange, similarly, is a within-cluster sub-axis dispute about what FLN actually contains. HCF want FLN to be sub-axis 1 narrowly construed (recursion); PJ want it broader (sub-axes 1 + parts of 3, including phonology and word-learning).

## What's not yet ground-truthed but should be before drafting

- **Lewis 1969 on convention** — for Population-level convention cluster.
- **Labov foundational work on speech communities** — already cited in HPC book Chapter 16, but read primary for cluster-template fidelity.
- **Haugen on standardization, Silverstein on monoglot standard / n-th-order indexicality, Agha 2007 on enregisterment, Bourdieu on legitimate language, Makoni and Pennycook on disinventing languages, Irvine and Gal on iconization and erasure** — for Named-sociohistorical-object cluster.
- **Hymes, Searle, Goffman** — for Communicative practice cluster. Most foundational; read at least one primary source for each.
- **Katz on linguistic Platonism, Montague, formal-language theory** — for Abstract formal system cluster.
- **Chomsky 1986, 1995, 2013; Devitt and Sterelny 1989; Devitt 2003, 2008** — for Idiolect / I-language cluster.
- **Hockett's design features** — for the boundary discussion of animal communication and the semiotic genus.
- **Pinker tweet 2026-04-25** — primary documentation if §1 cites public reception; the intake note mentions it. May need an `@misc` bib entry.

These are read-on-demand: the next-action is to populate the per-cluster template starting with Capacity, so Hauser-Chomsky-Fitch and Pinker-Jackendoff are the highest-priority next reads.
