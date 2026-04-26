# Per-cluster template — Abstract formal system

Drafted 2026-04-26 from the source-grounding pass. This file populates the per-cluster template for the Abstract formal system cluster (subsumes brainstorm #5 — language as a set-theoretic / formal object). It is the cluster of `language` claims about *formal grammars, set-theoretic objects, semantic models, mathematical-Platonist or formalist or fictionalist treatments of language as a formal entity*.

## Headline

The Abstract formal system cluster is the cluster of `language` claims about *language as a mathematical / formal object*: a set of strings with formal-definability properties; a system of meanings under model-theoretic interpretation; a Platonist or formalist or fictionalist abstract entity studied with the methods of mathematics. Santana 2016 §5 develops this as one of his three legitimate ontologies, distinguishing Platonism, formalism, and fictionalism as candidate philosophical positions on the abstract object.

The cluster has a special methodological niche: **extensional adequacy** is its working desideratum. As Santana puts it, "Extensional adequacy is an easier target to hit than accurate psychological description, so for practical purposes it's all that's required." This is what makes the cluster useful for NLP, for formal semantics' working analyses, for computational-linguistic applications. The cluster is unusual among the six in that its **stabilizers are not population-level usage** but **mathematical inheritance** — the formal-system tradition's commitments to set theory, model theory, computability theory, type theory.

## Sub-axis inventory

The cluster has at least four sub-axes:

1. **Formal-language theory (Chomsky hierarchy and beyond).** Languages as sets of strings; grammars as formal devices for generating / recognising those sets; the Chomsky hierarchy (regular / context-free / context-sensitive / computably enumerable); refinements (mildly context-sensitive, sub-regular). Jäger & Rogers 2012 is the canonical recent overview.
2. **Formal semantics (Montague tradition).** Languages as systems of meanings; meanings as model-theoretic objects (sets, functions, possible worlds); compositional rules mapping syntactic structure to semantic value. Montague's 1970s programme; type-theoretic developments; intensional and dynamic semantics.
3. **Mathematical-Platonist linguistics (Katz).** Linguistic objects (sentences, expressions) as Platonic abstracta — analogous to numbers in mathematical Platonism. Katz's 1981 *Language and Other Abstract Objects*; Katz 1984 "An Outline of Platonist Grammar."
4. **Computational / NLP working usage (Carnap, Dowty, NLP applications).** Languages as formal models that approximate natural-language phenomena well enough for practical purposes (parsing, generation, translation). Carnap-style methodological idealization; Dowty's Montague-grammar work; modern NLP including LLMs as boundary cases.

These are at different theoretical levels. (1) is mathematical-formal; (2) is mathematical-formal applied to meaning; (3) is metaphysical-realist about formal objects; (4) is methodological-instrumentalist. They share the formal-mathematical apparatus and the extensional-adequacy desideratum, but differ on what the formal objects actually are. Slippage occurs when claims travelling between sub-axes blur these ontological commitments.

## Per-sub-axis template

### 1. Formal-language theory

- **Paradigm cases.** The Chomsky hierarchy: regular ⊂ context-free ⊂ context-sensitive ⊂ computably enumerable (Jäger & Rogers 2012). Natural-language results: Chomsky's argument that English is not regular (centre embedding); Huybregts / Shieber's argument that Swiss German is not context-free (cross-serial dependencies); Culy on Bambara. Natural languages are at least mildly context-sensitive (Joshi's TAG, Stabler's MG / minimalist grammars). Sub-regular hierarchy: strictly k-local, k-testable.
- **Boundary cases.** The membership problem for various levels (decidable for context-sensitive; intractable in practice). Relations between formal-language complexity and processing complexity (cognitive plausibility of grammars at different levels). Programming languages — paradigm formal-language-theory entities, but with different stabilizers (institutional / engineering rather than usage). Animal communication systems mapped onto formal hierarchies (Gentner et al. on starlings; the Fitch-Hauser AnBn study cited HCF 2002).
- **Diagnostics.** Formal proofs that a given language is at a given level of the hierarchy (Chomsky's pumping-lemma proof for non-regularity of English; Shieber's proof for non-context-freeness of Swiss German). Computational complexity of membership / parsing problems. Chomsky-hierarchy inclusion proofs.
- **Stabilizers.** Mathematical inheritance: definitions of regular grammars, finite-state automata, context-free grammars, etc. are mathematically determinate. Definitional stipulation: the framework is what it is by formal definition. Disciplinary practice: the formal-language-theory community shares definitions and proof techniques. Maintenance grain: outside HPC-book ch 8's Levels 1-4 — the cluster's stabilizers are mathematical-disciplinary, not population-usage.
- **Projection target.** Observed P (a natural-language phenomenon — e.g., centre embedding, cross-serial dependency) licenses expected Q (the language is at least at hierarchy level X; cognitive mechanisms recognising the language must have at least the corresponding power) in unobserved cases. Defeated if D: the formal-language-theoretic characterisation turns out to be inadequate for the natural-language phenomenon (e.g., natural languages turning out to require even more power than mildly context-sensitive); the cognitive-mechanism inference fails because the formal-language-theory characterisation isn't actually the relevant cognitive mechanism (Jäger & Rogers note that for cognitive mechanisms, sub-regular and model-theoretic characterisations are more useful than the standard Chomsky-hierarchy ones).
- **Defeat conditions.** A natural-language phenomenon that requires unbounded power not captured by mildly context-sensitive (the recent literature on copy-language constructions in some languages may push this). The cognitive-mechanism / formal-language-theory mapping turning out to be looser than assumed (per Jäger & Rogers §5).
- **Slippage risks within the Abstract formal system cluster.**
  - Sub-axis 1 ↔ Sub-axis 3: formal-language-theory is mathematically determinate; mathematical-Platonist linguistics adds a metaphysical claim that the formal objects exist Platonistically. Slippage when the metaphysical claim is smuggled into purely formal-language-theoretic results, or when formal-language-theoretic results are taken to settle metaphysical disputes.
  - Sub-axis 1 ↔ Sub-axis 4: formal-language-theory's characterisation of natural languages is sometimes treated as the working object of NLP / computational linguistics. The slippage is when the formal idealisation is taken to be the natural-language object itself.
- **Slippage risks to other clusters.**
  - Sub-axis 1 → **Capacity (cross-cluster).** This is one of the most common cross-cluster slippages: formal-language-theoretic characterisations are read as evidence about the cognitive faculty (HCF 2002's Hypothesis 3 — recursion as the unique FLN — sits exactly here). The Pinker-Jackendoff 2005 critique focuses partly on this slippage. The conditioning-gain test would ask: does the formal-language-theoretic claim about natural languages condition on the cognitive-architecture variables relevant to processing them?
  - Sub-axis 1 → **Idiolect/I-language.** Chomsky's I-language is sometimes characterised in formal-language-theoretic terms (the I-language as a generator for a particular formal-language-theoretic set). Devitt 2008 worries about exactly this slippage: the linguistic conception (Sub-axis 2 of Idiolect cluster) reads formal-language-theory results as about the public language, not about the speaker.

### 2. Formal semantics (Montague tradition)

- **Paradigm cases.** Montague's 1970s programme: natural-language meanings as model-theoretic objects (functions, sets, possible-world structures). Compositional semantics: the meaning of a complex expression is determined by the meanings of its parts and the way they're combined. Type-theoretic developments. Quantifier-raising; intensional contexts; modal subordination; dynamic semantics (Heim, Kamp). The "Montague Grammar" / formal-semantics tradition broadly.
- **Boundary cases.** Phenomena that resist clean compositional analysis (idioms; metaphor; pragmatic enrichment; vagueness). Sign-language formal semantics (Zucchi 2012 in the literature folder). Semantics-pragmatics boundary cases. Formal models of social meaning (rare; usually modelled at a different level).
- **Diagnostics.** Compositional-semantic proofs (deriving meaning from structure + lexical entries). Truth-conditional analysis of sentences. Inference-pattern analysis (entailments, presuppositions, implicatures). Cross-linguistic universals at the semantic level (per Steedman 2020 in the Mendeley collection).
- **Stabilizers.** Mathematical inheritance (model theory, type theory, lambda calculus). Definitional stipulation. Disciplinary practice: the formal-semantics community shares foundational frameworks. Maintenance grain: outside HPC-book Levels 1-4; mathematical-disciplinary.
- **Projection target.** Observed P (a semantic property of an expression in some test cases) licenses expected Q (the same property in unobserved cases of similar structure; predictable inference patterns; cross-linguistic correspondences) in unobserved cases. Defeated if D: the formal-semantic characterisation fails to predict actual meaning judgements in new cases; cross-linguistic universals at the semantic level don't replicate; the formal model proves inadequate for some class of phenomena.
- **Defeat conditions.** Phenomena resistant to clean compositional analysis that the formal apparatus can't accommodate. A formal-semantic universal that fails cross-linguistically (Steedman 2020 examines several candidate universals).
- **Slippage risks within the Abstract formal system cluster.**
  - Sub-axis 2 ↔ Sub-axis 4: formal-semantic models are sometimes taken to be the natural-language meanings themselves rather than a model of them. Slippage when the model is treated as the modelled.
  - Sub-axis 2 ↔ Sub-axis 1: formal semantics is a different formal apparatus than formal-language theory; the two are sometimes conflated when "formal" is invoked.
- **Slippage risks to other clusters.**
  - Sub-axis 2 → **Capacity (cross-cluster).** Formal-semantic claims sometimes get read as claims about the cognitive semantic faculty. The slippage is at the model-vs-mechanism level (per HPC book ch 7's three uses of "mechanism": analyst diagnostic vs maintenance mechanism vs speaker mechanism).
  - Sub-axis 2 → **Communicative practice (cross-cluster).** Formal semantics treats meaning as truth-conditional / model-theoretic; communicative practice treats meaning as situated interactional achievement. The two project to different inferences.

### 3. Mathematical-Platonist linguistics (Katz)

- **Paradigm cases.** Katz's 1981 *Language and Other Abstract Objects*. Katz 1984 "An Outline of Platonist Grammar." The view that linguistic expressions are Platonic abstracta — analogous to numbers in mathematical Platonism. Grammars as theories of those abstract objects. Katz's argument (per Santana 2016 §5) that linguistic theory aims at extensional adequacy and can achieve it without commitment to psychological reality.
- **Boundary cases.** Devitt 2008 explicitly distances his linguistic conception from Katz's Platonism (Devitt's view is realism about *physical* SLEs, not about Platonic abstracta). The status of formal-semantic objects (functions, possible worlds) — these are clearly mathematical, but are natural-language sentences also? Programming languages — paradigmatic formal-system entities, but rarely claimed to be Platonic.
- **Diagnostics.** Theoretical-philosophical argument about the metaphysics of abstract objects. Reduction or non-reduction of linguistic theory to other sciences (mathematics, psychology, sociology). Examination of the working ontological commitments of grammar-construction practice.
- **Stabilizers.** Mathematical-philosophical-Platonist tradition. Disciplinary practice in the (smaller) Platonist-leaning subset of formal linguistics. Maintenance grain: philosophical-disciplinary.
- **Projection target.** Observed P (a structural pattern in linguistic data) licenses expected Q (the same pattern reflects a Platonist-objective fact about the abstract object; the pattern's universality is grounded in the abstract object's structure) in unobserved cases. Defeated if D: alternative ontologies (psychological, social, conventionalist) explain the patterns equally well; the Platonist commitment turns out to be doing no explanatory work.
- **Defeat conditions.** Successful explanation of all the relevant phenomena via alternative ontologies. The fictionalism alternative (Santana §5 mentions): linguistic theory is consistent with the linguistic objects being "fictions" (analogous to mathematical fictionalism). If fictionalism captures everything Platonism does without the metaphysical commitment, Platonism is undermined.
- **Slippage risks within the Abstract formal system cluster.**
  - Sub-axis 3 ↔ Sub-axis 1: formal-language-theoretic results are sometimes taken to support Platonism, but they don't (the formal apparatus is consistent with multiple metaphysical positions including formalism and fictionalism).
  - Sub-axis 3 ↔ Sub-axis 4: NLP and computational-linguistics practice doesn't typically commit to Platonism. The sub-axis distinction is between metaphysical commitment (3) and methodological convenience (4).
- **Slippage risks to other clusters.**
  - Sub-axis 3 → **Idiolect/I-language.** Devitt 2008 explicitly distances himself from Katz's Platonism. The boundary is non-trivial: Devitt is realist about physical SLEs with conventional properties, which is not Platonism. But the Platonist position can be misread as a position about individual linguistic objects.

### 4. Computational / NLP working usage

- **Paradigm cases.** Modern NLP applications: parsers, generators, machine translation systems, large language models. Carnap-style methodological idealization: study language via constructed simplified models first. Dowty's working stance: formal-semantic analyses don't need to be psychologically real. Programming languages as paradigmatic formal-system entities. LLMs as a distinctive boundary case.
- **Boundary cases.** Modern LLMs (already a boundary phenomenon in Brett's `LLMs_as_boundary_phenomena` paper) — they exhibit extensive extensional adequacy on natural-language tasks while being computationally distant from formal-language-theoretic characterisations. The status of LLM-internal representations: are they instances of any formal-language-theoretic class? Programming-language designers borrowing from natural-language formal theory.
- **Diagnostics.** Performance benchmarks. Cross-task generalisation. Computational-complexity analysis of running systems. Formal verification of system properties.
- **Stabilizers.** Engineering tradition. Computational-linguistic disciplinary practice. Mathematical inheritance. Maintenance grain: engineering / computational-disciplinary.
- **Projection target.** Observed P (a system's performance on a class of natural-language tasks) licenses expected Q (similar performance on similar tasks; transfer to related tasks; predictable failures on tasks outside the class) in unobserved cases. Defeated if D: performance fails to transfer; predicted failures don't materialize; the formal model doesn't capture the regularity it appears to capture.
- **Defeat conditions.** Cross-task generalisation failures that the formal model doesn't predict. LLM-style systems achieving extensional adequacy without instantiating the formal-language-theoretic class their domain belongs to (the situation we're approximately in now with frontier LLMs).
- **Slippage risks within the Abstract formal system cluster.**
  - Sub-axis 4 ↔ Sub-axis 1: NLP practice often borrows from formal-language theory but at varying levels of fidelity. The slippage is treating an NLP-tractable approximation as if it were the formal-language-theoretic characterisation.
  - Sub-axis 4 ↔ Sub-axis 3: NLP practice typically eschews Platonist commitments; the slippage is when NLP successes are read as supporting Platonism.
- **Slippage risks to other clusters.**
  - Sub-axis 4 → **Capacity (cross-cluster).** LLM successes are routinely read as evidence about Capacity (faculty / processing-architecture / developmental-acquisition / impairment). This is the mirror image of Casten/Pinker: there, biological evidence is read as architectural; here, computational evidence is read as architectural.
  - Sub-axis 4 → **Communicative practice (sub-axis 1 speech-acts / sub-axis 4 metapragmatic).** LLM outputs are routinely treated as data about Communicative practice. The slippage is when LLM-generated speech-act-typical outputs are taken to bear on human speech-act conventions or interactional norms (mentioned in the Communicative-practice template's worked-example B).

## Cross-sub-axis slippage map (within the Abstract formal system cluster)

```
       1. Formal-language theory (Chomsky hierarchy)
                          \   /
                           \ /
                          ←→
                           |
       2. Formal semantics (Montague)
                          \   /
                           \ /
                          ←→
                           |
       3. Mathematical-Platonist linguistics (Katz)
                          \   /
                           \ /
                          ←→
                           |
       4. Computational / NLP working usage (Carnap, Dowty, NLP, LLMs)
```

Most-frequently-traversed slippage edges:
- 1 ↔ 4 (formal-language theory vs NLP working approximation — the model-vs-modelled slippage)
- 3 ↔ 1, 2, 4 (Platonist metaphysics being smuggled into purely formal results)
- 1 ↔ 2 (formal-language vs formal-semantic apparatus conflated)

## Cross-cluster slippage risks

| Abstract-formal-system sub-axis → other cluster | What gets smuggled |
|--------------------------------------------------|--------------------|
| Sub-axis 1 → Capacity | Formal-language-theoretic characterisations read as evidence about cognitive faculty (HCF 2002 Hypothesis 3 sits here) |
| Sub-axis 1 → Idiolect/I-language | Formal-language characterisation of natural language read as either I-language (Chomsky) or external-linguistic-reality (Devitt) without distinguishing the cluster boundary |
| Sub-axis 2 → Capacity | Formal-semantic models read as evidence about cognitive semantic faculty |
| Sub-axis 2 → Communicative practice | Formal-semantic / truth-conditional meaning read as evidence about situated interactional meaning |
| Sub-axis 3 → Idiolect/I-language | Platonist linguistics easily mis-read as a claim about individual mental objects (which Katz himself rejects) |
| Sub-axis 4 → Capacity | LLM successes / failures read as evidence about Capacity sub-axes (faculty / architecture / developmental / impairment) |
| Sub-axis 4 → Communicative practice | LLM outputs treated as data about human Communicative practice |
| Sub-axis 4 → Population-level convention | NLP corpus statistics treated as direct evidence about population-level conventions |

## Worked example: HCF 2002 recursion-only as Abstract-formal-system → Capacity slippage

The HCF 2002 recursion-only hypothesis sits exactly at the Sub-axis 1 → Capacity Sub-axis 1 cross-cluster boundary. **Recursion** as a formal-language-theoretic property has determinate mathematical content (centre-embedding-supporting; non-finite-state). **The cognitive faculty** is at a different ontological grain. HCF claim that FLN comprises only recursion + interfaces. PJ 2005 argue that this conflates a formal-language-theoretic property with a cognitive-faculty claim — and that the recursion-only hypothesis is "motivated by Chomsky's recent approach to syntax, the Minimalist Program, which de-emphasizes the same aspects of language. The approach, however, is sufficiently problematic that it cannot be used to support claims about evolution."

In our terms: the slippage is from a formal-language-theory characterisation (Sub-axis 1 of Abstract formal system) to a Capacity-cluster claim (Sub-axis 1 of Capacity, faculty / processing-architecture). The two sub-axes have different stabilizers: formal-language theory has mathematical-disciplinary stabilizers; Capacity-faculty has biological / architectural stabilizers. The Minimalism move bundles them by treating the formal-language-theoretic characterisation as if it were the cognitive-faculty characterisation. Per HPC book ch 7's three uses of "mechanism," this is the analyst diagnostic (formal-language-theoretic apparatus) being treated as the maintenance / cognitive mechanism.

This is a useful cross-cluster slippage worked example because:
- It's already source-grounded (HCF 2002, PJ 2005, FHC 2005, JP 2005 all read).
- It bridges a major academic dispute that working linguists know about.
- It illustrates the slippage diagnostic at high resolution.
- §9 can use it alongside the Casten/Pinker case.

## Length and integration notes for §8 drafting

§8 (the Abstract formal system cluster section, last per the architecture) should:

- Open with the cluster's distinctive niche: extensional adequacy as the working desideratum, mathematical-disciplinary stabilizers rather than population-usage stabilizers.
- Engage Santana §5 directly — Platonism, formalism, fictionalism as candidate ontologies; Santana's argument that the abstract ontology is legitimate even if of less interest than psychological / social.
- Anchor sub-axis 1 with Jäger & Rogers 2012 (already source-grounded); Steedman 2020 (in Mendeley); Chomsky 1957 / 1965 / 1995 references.
- Anchor sub-axis 2 with Montague 1970s programme; relevant secondary reviews; Zucchi 2012 sign-language formal semantics (in literature folder).
- Anchor sub-axis 3 with Katz 1981, 1984 (need primary verification before §8 prose).
- Anchor sub-axis 4 with NLP / LLM as a contemporary boundary case; reference to Brett's `LLMs_as_boundary_phenomena` paper for the deeper analysis.
- Word budget estimate: 1500-1800 words. Include the HCF/PJ recursion-only worked example as a forward reference to §9.

## What this template doesn't yet address

- **Katz 1981 *Language and Other Abstract Objects*** primary — Brett may have it. Should be source-grounded if Platonism is engaged substantively. Santana 2016 §5 already gives a careful characterisation.
- **Katz 1984 "An Outline of Platonist Grammar"** primary — same status.
- **Montague's 1970s papers** primaries — Brett may have key papers. Most recent formal-semantics handbooks would also serve.
- **Steedman 2020 *A formal universal of natural language grammar*** — in Mendeley; not yet sampled. A current state-of-the-art primary on a formal-language-theoretic universal.
- **Tomasello 2005 *Beyond formalities*** — in Mendeley; relevant for the sub-axis 4 critique of formalism.
- **Chomsky 1957 *Syntactic Structures*** — the foundational formal-language-theoretic work. Almost certainly sourceable; central to sub-axis 1.
- **Tomasello / usage-based critiques of formalism** — relevant to the cluster boundary with Capacity and Communicative practice.

These are read-on-demand; they don't block §8 drafting.
