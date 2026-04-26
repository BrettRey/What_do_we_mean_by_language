# Per-cluster template — Communicative practice

Drafted 2026-04-26 from the source-grounding pass. This file populates the per-cluster template for the Communicative practice cluster (subsumes brainstorm #6 "communicative behaviour" and #7 "modality"). Per HANDOFF, this is the second cluster templated because it carries the most operationalisation-slippage material and the metapragmatic-typification machinery that §9 leans on.

## Headline

Communicative practice is the cluster of `language` claims made about *what speakers are doing when they communicate*: the conventionalized actions, the interactional uptake, the socially-recognised speech, and the register dynamics through which language travels in social life. The cluster is moderately fat — it contains identifiable sub-axes — but more unified than Capacity, because the sub-axes share stabilizers (alignment, metapragmatic typification, joint action) and project to an overlapping range of inferences (predicting how speakers will deploy and interpret language in social contexts).

The primary slippage risk for this cluster is **operationalisation-slippage**: confusing the analyst's diagnostic device (a corpus of recorded interaction; a treebank annotated by trained linguists; an LLM-output trace) with the maintenance mechanism (the situated interactional work speakers actually do). Per the HPC book chapter 7's three uses of "mechanism" (maintenance / speaker / analyst-diagnostic), most operationalisation slippages collapse the third into the first.

## Sub-axis inventory

The Communicative practice cluster spans four theoretical traditions with overlapping but distinct projection targets:

1. **Speech-act / illocutionary force (Searle, Austin).** Conventionalized communicative actions; constitutive rules for promises / requests / assertions / declarations.
2. **Interactional / situational organization (Goffman, conversation analysis).** Face-work, deference, framing, footing; the moral / social order of conversation.
3. **Communicative competence / appropriateness (Hymes 1992).** The capacity to use language appropriately in context; the four sectors of judgement (formally possible, feasible, appropriate, in fact done).
4. **Metapragmatic typification / register / enregistered voice (Agha 2003, 2005; Silverstein; Eckert 2008).** The reflexive models of speech that allow speakers to recognize and deploy social meanings.

Plus a cross-cutting axis:

5. **Modality (speech / sign / writing / gesture).** Brainstorm #7 folded in; affects what's afforded by each sub-axis above.

These are not independent: a speech act (sub-axis 1) is performed in an interactional context (sub-axis 2), evaluated against appropriateness norms (sub-axis 3), with register-indexed social meanings (sub-axis 4), in a particular modality (sub-axis 5). They cluster more tightly than the Capacity sub-axes did. But they project to different inferences, so claims travelling between them require explicit warrant.

## Per-sub-axis template

### 1. Speech-act / illocutionary force

- **Paradigm cases.** Promises, requests, assertions, declarations, apologies, oaths, performatives ("I now pronounce you..."). Felicity conditions (Austin's preparatory / sincerity / essential conditions). Direct vs indirect speech acts ("Can you pass the salt?" as a request, not a question about ability). Searle's taxonomy: representatives, directives, commissives, expressives, declarations.
- **Boundary cases.** Speech acts in non-canonical formats (text messages, social-media posts, automated assistant outputs). Speech acts performed by groups (institutional declarations). Speech acts in non-spoken modalities (signed promises; written contracts). Expressives that index without explicitly naming a speech act ("Thrilled to be delivering the annual lecture" — the social-media public-announcement fragment from HPC book ch 16). LLM-generated speech-act-like outputs (a chatbot saying "I'm sorry" — does it perform an apology?).
- **Diagnostics.** Felicity / infelicity judgements. The reportability test (can be reported with the relevant speech-act verb: "She promised that..."). Compositional analysis of illocutionary force from explicit performative verbs + context + form.
- **Stabilizers.** Conventionalized constitutive rules at the population level (per Searle 1969: speech-act types are constituted by rules, not just regulated by them). Acquisition: children acquire speech-act conventions early (per Hymes 1992: appropriateness and grammar are acquired in the same developmental matrix). Institutional infrastructure for high-stakes speech acts (legal performatives, religious oaths, ceremonial declarations). Maintenance grain: HPC-book Levels 2 and 3 (population + conditioning variables) primarily; Level 1 (individual capacity) for execution; Level 4 (institutional) for institutionally-stabilised types.
- **Projection target.** Observed P (a speech-act-type-conventional form deployed in context X) licenses expected Q (the speech act has been performed; the relevant felicity conditions are operative; predictable interactional consequences ensue) in unobserved cases. Defeated if D: the form fails to count as the speech-act type for participants in the actual interaction (mis-coordination; cultural difference in conventions; ironic / mock deployment).
- **Defeat conditions.** Cross-cultural variation that resists Searle's universal-speech-act-types claim (some communities don't have a speech act of "promise" in the Western sense; some have speech acts without obvious Western analogues). Fictional / role-played performances that mimic speech-act forms without the constitutive rules being engaged. LLM-generated outputs that trigger reportability without speaker accountability — boundary case rather than counterexample.
- **Slippage risks within the Communicative practice cluster.**
  - Sub-axis 1 ↔ Sub-axis 2: speech-act types vs interactional sequences. A request and the response form an adjacency pair (CA tradition); whether to analyse at the speech-act level or the sequence level depends on the question. Slippage occurs when speech-act-type analyses ignore the interactional embedding that determines which type is being performed.
  - Sub-axis 1 ↔ Sub-axis 3: appropriateness in Hymes's sense supersedes felicity in Searle's. Hymes 1992 explicitly cites Searle but argues that the speech-act level needs to be embedded in a four-sector framework. Slippage occurs when felicity-condition analyses are read as direct evidence about appropriateness.

### 2. Interactional / situational organization

- **Paradigm cases.** Face-work and deference (Goffman 1956, 1967). Framing and footing (Goffman; how participants negotiate what kind of interaction they're in). Adjacency pairs (CA tradition). Repair sequences. Turn-taking. The waiter saying "And yourself?" as deference-indexing (HPC book ch 16). Participation frameworks (who speaks, who listens, who's overhearing).
- **Boundary cases.** Asynchronous / mediated interaction (email exchanges, social-media threads). Multi-party interactions where participation framework shifts. Cross-cultural variation in interaction order. Animal communication that has interactional structure but lacks face-work in the Goffmanian sense. Computer-mediated exchanges including LLM-mediated.
- **Diagnostics.** Conversation-analytic transcription; identification of repair sequences, turn-allocation, adjacency pairs. Goffmanian analysis of face-work, framing, footing. Detection of interactional violations / repairs as evidence about underlying norms.
- **Stabilizers.** Interactive alignment at the dyadic / small-group level (Pickering & Garrod 2004). Cultural transmission of interactional conventions (acquired in childhood, varies cross-culturally). Institutional gatekeeping for high-stakes interactional contexts (courtroom, classroom, medical encounter). Conventionalization at the cultural level — the interaction order varies systematically across cultures (Eastern vs Western face concerns; high-context vs low-context cultures). Maintenance grain: HPC-book Levels 1, 2, 3, 4 — distributed across all four; the interaction order is one of the most multiply-stabilised aspects of communication.
- **Projection target.** Observed P (an interactional move or sequence in context X) licenses expected Q (predictable response from interlocutor; predictable repair if the move violates a norm; predictable face-consequences) in unobserved cases. Defeated if D: cross-cultural transfer fails systematically; the predicted response doesn't follow because some unmodelled stabilizer is operative.
- **Defeat conditions.** A claimed interactional universal (turn-taking; preference for self-repair) that fails to replicate in some culture. Asymmetric fraying (P1): if the interaction-order cluster fails along expected lines (high-stakes contexts holding while low-stakes ones drift), the maintenance story is supported; if drift is uniform, the interaction-order claim is undermined. The conditioning-gain test (P5): conditioning on context-type / participant-relationship should improve prediction of interactional moves; if it doesn't, the cluster is fragile.
- **Slippage risks within the Communicative practice cluster.**
  - Sub-axis 2 ↔ Sub-axis 4: interactional patterns and metapragmatic typifications are not independent. The deference index in "and yourself?" works because the form is enregistered as deferential — register-level recognition (sub-axis 4) is what makes the interactional deployment (sub-axis 2) work. Slippage occurs when interaction-analysis is read as direct evidence about register-level enregisterment without showing the metapragmatic step.
  - Sub-axis 2 ↔ Sub-axis 3: Goffman's interactional competence is part of what Hymes's communicative competence covers. The traditions overlap; slippage at the analytical level is treating one as the whole.

### 3. Communicative competence / appropriateness (Hymes 1992)

- **Paradigm cases.** Hymes's four sectors of judgement: formally possible (grammaticality), feasible (psycholinguistic implementation), appropriate (in relation to context), in fact done (actual performance). The speech community's competence includes all four. Hymes's worked examples: White Thunder (Bloomfield 1927) — a Menominee speaker with limited Menominee resources, atrocious by community standards, but typical in the impacted-by-acculturation generation. Red Cloud Woman — speaks "beautiful and highly idiomatic Menominee, Ojibwa, and Potawatomi" — would correspond to a "highly educated American woman who spoke, say, French and Italian in addition to the very best type of cultivated, idiomatic English." Hymes's emphasis: differential competence within a heterogeneous speech community.
- **Boundary cases.** Late second-language learners with full grammatical competence but limited appropriateness-knowledge. Heritage speakers whose first sector (formal possibility) holds but whose third (appropriateness) drifts. Children's developing communicative competence (Hymes 1992 cites Ervin-Tripp on early acquisition of register / address-form rules). LLM outputs that are formally possible and feasible but whose appropriateness varies by deployment context. Multilingual speakers whose competence varies by code (Hymes's Burundi example: peasants address herders with halting / clumsy speech vs full verbal competence in everyday).
- **Diagnostics.** Hymes's four-sector judgements applied separately. Cross-context elicitation (does a speaker accept the form in context X but not Y?). Verbal-repertoire assessment (Gumperz 1964) — what codes / subcodes does an individual command? Analysis of sociolinguistic interference between codes.
- **Stabilizers.** Acquisition (children acquire appropriateness rules in the same developmental matrix as grammar — Hymes 1992 explicitly). Interactive alignment in real time (per Pickering & Garrod). Community-level transmission of register / address-form / domain conventions. Institutional gatekeeping for some sectors (e.g., professional registers, formal-writing norms). Maintenance grain: Levels 1, 2, 3 — speaker dispositions, population distributions, and conditioning variables (dialect, register, discourse community).
- **Projection target.** Observed P (a speaker's performance across multiple contexts) licenses expected Q (predictable performance in unobserved contexts of similar conditioning; predictable repair if appropriateness is violated; predictable judgements about inappropriate uses by other speakers) in unobserved cases. Defeated if D: the speaker's performance is not conditioned on context in expected ways (might suggest sector-3 competence is not in fact present).
- **Defeat conditions.** A claimed appropriateness rule that doesn't replicate across speakers. The conditioning-gain test specifically: if Hymes's appropriateness sector is real, conditioning on context-variables should improve prediction. If it doesn't, the appropriateness story collapses to grammatical-and-feasible-only.
- **Slippage risks within the Communicative practice cluster.**
  - Sub-axis 3 ↔ Sub-axes 1, 2, 4: Hymes 1992's framework is explicitly designed to integrate speech-act-theoretic, interactional, and metapragmatic moves into one competence-theoretic framework. The slippage risk is treating Hymes's framework as a competing position rather than as a meta-framework that subsumes the other three traditions.
  - Sub-axis 3 ↔ **Capacity (cross-cluster).** Hymes's first sector (formally possible / grammaticality) is a Capacity-cluster claim. Hymes 1992 deliberately keeps these separate — he wants to broaden competence to include the other three sectors but explicitly distinguishes them from the formally-possible sector. Slippage here is letting communicative-competence claims be read as Capacity claims (or vice versa).

### 4. Metapragmatic typification / register / enregistered voice (Agha 2003, 2005)

- **Paradigm cases.** Agha's concept of enregisterment: "processes whereby distinct forms of speech come to be socially recognized (or enregistered) as indexical of speaker attributes by a population of users" (Agha 2005: 38). Voice = the speaker-attributes a form indexes. Register = "reflexive models of speech and conduct that depend for their existence on processes of enregisterment." Examples: Received Pronunciation as enregistered for educated / upper-middle-class British speakers. The "and yourself?" waiter form (HPC book ch 16) — enregistered as deferential service-encounter speech. The "Thrilled to be delivering..." social-media public-announcement fragment (HPC book ch 16) — enregistered as compressed-public-gratitude. Eckert's indexical field (2008): an ideologically structured space of potential social meanings carried by a form.
- **Boundary cases.** Forms that are partially enregistered (recognised by some but not others; emerging registers; declining registers). Forms that index multiple registers depending on context (the inverse of one form / one register). Cross-cultural register transfer. Internet registers (Reddit speech, academic-Twitter, etc.) — Hp book ch 16 flags "internet English" as a fat class because it covers Reddit + formal blogs + arxiv preprints, too much internal diversity. Pre-enregistered emerging forms.
- **Diagnostics.** Source-attribution / indexical-inference experiments: hear a form, infer a speaker-type, confirm or disconfirm against population data. Looking for metapragmatic discourse (talk about the form: "that sounds posh", "that's a Reddit thing"). Sociolinguistic-interview data on register-recognition. Population-level frequency data conditioned on speaker-type.
- **Stabilizers.** Reflexive social cognition (the metapragmatic level — speakers know what forms index what). Interactive alignment + divergence (HPC book ch 16: convergence tightens clusters from within; divergence sharpens boundaries from without). Institutional reinforcement for prestige registers (schooling, media, editorial gatekeeping). Looping feedback (Hacking 1999): once a form is enregistered, speakers' awareness of the indexical link shapes their use, which reinforces the link. Maintenance grain: Levels 2, 3, 4 primarily — population distributions + conditioning variables + institutional loops; Level 1 only as the locus of individual recognition.
- **Projection target.** Observed P (a form deployed in context X by speaker Y) licenses expected Q (other community members will infer speaker-attributes Z; the form will pattern with other registered features in similar contexts; the form's use will index a recognisable persona) in unobserved cases. Defeated if D: the predicted indexical inferences fail; the form-register link doesn't replicate in another community; the form's use doesn't pattern with the rest of the register.
- **Defeat conditions.** A claimed register that is not in fact recognised by the population (i.e., no metapragmatic awareness; no reflexive discourse about the register). Asymmetric fraying along stabilizer lines: if the prestige-register peripheral features fail under reduced institutional reinforcement while core features hold, the institutional-loops stabilizer is supported. The conditioning-gain test: conditioning on speaker-type / context should improve register-form prediction; if it doesn't, the register isn't doing the work claimed for it.
- **Slippage risks within the Communicative practice cluster.**
  - Sub-axis 4 ↔ Sub-axis 2: register-level analyses can ignore the interactional moment-by-moment work that maintains them; interactional analyses can ignore the register-level recognition that gives forms their meaning. The two sub-axes are tightly coupled but distinct.
  - Sub-axis 4 ↔ **Named sociohistorical object (cross-cluster).** Named-language objects (English, Japanese, Cantonese) are themselves enregistered phenomena at scale. Slippage between Communicative-practice register-level claims and Named-sociohistorical-object claims about institutionally-stabilized named varieties.

### 5. Modality (cross-cutting)

- **Paradigm cases.** Speech (spoken language). Sign (sign languages: ASL, BSL, Auslan, etc.). Writing (alphabetic, logographic, syllabic). Gesture (co-speech gesture, semaphores, formal sign systems). Drumming systems (whistled / drummed languages). Multimodal communication (speech + gesture; sign + facial expression).
- **Boundary cases.** Internet-mediated written-but-quasi-spoken modes (chat, SMS — fast, intermal, real-time-ish but written). Computer-generated speech (TTS, LLM voice agents). Sign systems at the boundary of "language" (home sign; emerging sign languages; gestural pidgins). Programming languages (have written form, are designed to be performable, but lack many features of natural language).
- **Diagnostics.** Modality-specific experimental paradigms (sign-language acquisition; speech vs gesture in priming experiments; reading vs listening comprehension). Comparative analysis across modalities of the same propositional content.
- **Stabilizers.** Modality-specific neural architecture (Sandler et al. 2005 on the emergence of grammar in sign language). Modality-specific transmission infrastructure (literacy institutions for writing; signing communities for sign). Modality-specific affordance (writing supports asynchrony and durability; signing supports simultaneous-multichannel; speech supports prosody and rapid turn-taking).
- **Projection target.** Observed P (a communicative pattern in modality M) licenses expected Q (similar patterns in modality M' to the extent that stabilizers transfer across modalities; modality-specific variations that don't transfer) in unobserved cases. Defeated if D: modality-specific patterns fail to transfer when stabilizers are similar; modality-typical patterns appear in modalities that lack the relevant stabilizers.
- **Slippage risks within the Communicative practice cluster.**
  - Sub-axis 5 ↔ all other sub-axes: claims made about speech (sub-axes 1-4 paradigm cases all assume spoken interaction) may not transfer to writing or sign without explicit modality work. The classic case: studies of "speech" that exclude sign languages and then make universal claims.
  - Sub-axis 5 ↔ **Capacity (cross-cluster).** Modality-flexibility is a Capacity claim (humans can acquire spoken or signed languages with the same developmental trajectory). Communicative practice modality is a use claim. Slippage between these is one of the §1-hook-style sub-axis confusions.

## Cross-sub-axis slippage map (within the Communicative practice cluster)

```
            1. Speech-act / illocutionary force (Searle, Austin)
                          \   /
                           \ /
                          ←→
                           |
            2. Interactional / situational organization (Goffman, CA)
                          \   /
                           \ /
                          ←→
                           |
            3. Communicative competence / appropriateness (Hymes)
                          \   /
                           \ /
                          ←→
                           |
            4. Metapragmatic typification / register / voice (Agha, Eckert)
                          
                  cross-cuts all of 1-4 ↑
                           |
            5. Modality (speech / sign / writing / gesture)
```

Most-frequently-traversed slippage edges:
- 1 ↔ 2 (speech-act type vs interactional sequence)
- 2 ↔ 4 (interactional move vs register-level enregistered voice)
- 1 ↔ 3 (felicity in Searle's sense vs appropriateness in Hymes's)
- 5 → all (modality-specific findings projected to modality-general claims)

## Cross-cluster slippage risks

| Communicative-practice sub-axis → other cluster | What gets smuggled |
|------------------------------------------------|--------------------|
| Sub-axis 1 → Capacity | Speech-act competence treated as evidence about Capacity-faculty / language-architecture |
| Sub-axis 2 → Population-level convention | Interactional patterns treated as direct evidence about Lewis-style coordination conventions, ignoring metapragmatic mediation |
| Sub-axis 3 → Capacity | Hymes's appropriateness sector conflated with Capacity-as-acquisition (children acquire both, but they project differently) |
| Sub-axis 4 → Named sociohistorical object | Register-level enregistered voices conflated with named-language objects (English, AAVE, etc.) when the registers are sub-named-language varieties |
| Sub-axis 4 → Idiolect / I-language | Register-knowledge treated as evidence about individual mental grammar; Devitt-style sociolinguistic answer would push back |
| Sub-axis 5 → Capacity | Modality-flexibility-of-use treated as evidence about modality-flexibility-of-Capacity (the latter is broader and depends on biological architecture) |

## The operationalisation-slippage worked example (for §9)

Per HANDOFF, this cluster carries the operationalisation-slippage material that §9 catalogues. The pattern:

**Schema.** "X IS the language" — where X is some operationalised analyst-diagnostic (corpus, treebank, gram​mar-as-analyst's-product, competence judgements, LLM output) treated as the maintenance mechanism / the cluster itself.

**Worked example A: "The corpus IS the language."**

- A research project takes a corpus (Penn Treebank, BNC, COCA, or similar) and treats it as direct evidence about Communicative practice in the source community.
- The corpus is an artifact of: editorial selection (which texts are included); annotation conventions (POS tags, parse-trees, semantic frames); register selection (what registers are over- or under-sampled); curation choices (what years, what sources, what genres). Per HPC book chapter 8: "A category that predicts well across the British National Corpus, the Corpus of Contemporary American English, and the Penn Treebank may do so because all three were annotated by linguists trained in the same tradition, not because the category tracks stable structure in ordinary speech."
- The slippage is treating cross-corpus convergence (a sign of shared annotation conventions) as evidence about cross-community convergence (a claim about Communicative practice at the population level).
- Per the three-uses-of-mechanism distinction (HPC book ch 7): the corpus is an analyst diagnostic; the maintenance mechanism is interactive alignment + metapragmatic typification + transmission across the actual speech community. The slippage conflates the two.
- Diagnosis in HPC terms:
  - **Cluster check.** The corpus may show consistent property co-occurrence — but the consistency tracks annotation conventions, not population-level Communicative practice.
  - **Homeostasis check.** Perturbation test: if the annotation conventions changed but the underlying population-level practice didn't, would the corpus pattern persist? No — which reveals the corpus pattern as a sign of annotation-stabilizer not population-stabilizer.
  - **Projectibility check.** The corpus's predictions project to other corpora annotated by the same tradition; they don't necessarily project to the population's actual interactional behaviour. **No conditioning gain on actual-population variables → maintenance claim unsupported.**

**Worked example B: "The LLM output IS the language."**

- An analyst takes LLM completions of speech-act-typical prompts as evidence about how speakers perform the speech acts in question. (Or: takes LLM dialogue-generation as evidence about Communicative practice.)
- The LLM output is an artifact of: training-data curation (which corpora, which registers); RLHF tuning (what's been reinforced as desirable); prompt engineering (what's being asked); decoding strategy (temperature, top-k, top-p).
- The maintenance mechanism for human Communicative practice is situated interactional work, not LLM-internal processing. The LLM trace is an analyst diagnostic of training-data + tuning patterns; treating it as a maintenance mechanism conflates the two.
- This is closely related to but distinct from the LLM-as-boundary-phenomenon question (covered in Brett's `LLMs_as_boundary_phenomena` paper). Here the issue is methodological: treating LLM output as evidence about human Communicative practice, not whether LLMs themselves are members of the cluster.

**Worked example C: "The treebank IS the language."**

- An annotated treebank's structural properties are read as direct evidence about the syntactic system shared by the population.
- The treebank is an artifact of theoretical commitments encoded in the annotation scheme. CGEL annotations and dependency-grammar annotations of the same corpus produce different property-distributions; that's not evidence about the underlying population's competence — it's evidence about annotation-scheme commitments.
- Distinguishable from corpus case A above only by emphasis on theoretical-framework encoding rather than register / curation.

**The general diagnosis for §9.** Operationalisation-slippage cases share a structure: an analyst's diagnostic for the cluster (what *they* use to identify it, per HPC book chapter 7) gets treated as the maintenance mechanism for the cluster (what holds the cluster together in the world). The slippage is invisible because the diagnostic does in fact track *something* — but what it tracks is the analyst-tradition stabilizer (institutional, methodological, theoretical), not the cluster's own stabilizers. The conditioning-gain diagnostic catches this: if you condition on real-world speaker-population variables, the analyst-diagnostic's predictions should improve; if they don't, the diagnostic is tracking something other than the cluster.

## Length and integration notes for §6 drafting

§6 (the Communicative practice cluster section) should:

- Open with the sub-axis structure briefly (the four theoretical-tradition sub-axes plus the cross-cutting modality axis).
- Anchor each sub-axis with paradigmatic citations: Searle 1969 / Austin for sub-axis 1; Goffman 1967 (Interaction Ritual) for sub-axis 2; Hymes 1992 for sub-axis 3; Agha 2005 for sub-axis 4; Sandler et al. 2005 (already in literature folder) for sub-axis 5.
- Treat the worked operationalisation-slippage example as a *forward reference* to §9 — set up the example here briefly, develop it in §9.
- Engage the §9 forward reference by foregrounding the "no conditioning gain, no maintenance claim" methodological commitment and showing how it applies specifically to Communicative-practice claims.
- Word budget estimate: 1500-1800 words for §6. Slightly less than §3 (Capacity) because the within-cluster sub-axes overlap more and don't require the same individuation work.

## What this template doesn't yet address

- **Goffman 1967 (Interaction Ritual)** primary source — should be source-grounded before §6 prose-drafting if cited substantively. Hymes 1992 cites Goffman 1956, 1959, 1963, 1964, 1967 extensively; Brett's `references.bib` has Goffman entries but I haven't read the primaries.
- **Searle 1969 (Speech Acts) and Searle 1979 (Expression and Meaning)** primaries — same status. Hymes 1992 cites Searle 1967 (which appears to be a 1967 publication referenced as Searle's early work). Bib has searle1969 and searle1979.
- **Austin 1962 (How to Do Things with Words)** primary — the foundational performatives paper. Bib status to check.
- **Silverstein** on metapragmatics / orders-of-indexicality — referenced in PLAN.md for the Named-sociohistorical-object cluster but also relevant here for sub-axis 4.
- **Eckert 2008 indexical field** primary — in HPC book ch 16's reference list; could be source-grounded if §6 leans on it.
- **Pickering & Garrod 2004 interactive alignment** — also referenced in HPC book ch 16; a primary read would help ground sub-axes 2 and 3.
- **Sandler, Meir, Padden, Aronoff 2005** on the emergence of sign-language grammar — already in the literature folder (`sandler-etal2005-emergence-grammar.md`); should be sampled when sub-axis 5 (modality) is written into §6.
- **Hymes 1992 cites Bernstein 1965 on elaborated and restricted codes** as a converse case to the Paraguay Spanish/Guarani example. If Bernstein gets cited, primary verification needed.
- **The HCF / PJ exchange contains material relevant to Capacity sub-axes 1-2**, but PJ 2005's section on syntax (with case, agreement, etc.) is also relevant to Communicative practice sub-axis 1's "what counts as conventionalized communicative form." A pass-through cross-reference would tighten §3 and §6.

These are read-on-demand; they don't block §6 drafting.
