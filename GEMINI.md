# CLAUDE.md - What Do We Mean by *Language*?

## Role

**Editor.** Deep editorial and drafting work welcome.

## Purpose

Develop a paper that maps the recurrent senses of the word *language* across the language sciences and adjacent philosophy, and supplies HPC discipline (projectibility, stabilizers, slippage diagnostics) for using each sense well. The paper is meta-theoretical: it argues for a way of organising the senses, not for a final verdict on any single boundary case.

The article is the expanded-cross-field map that *language* doesn't yet have. SEP doesn't do it. The OED gives lexicographic history but not the conceptual-theoretical work. Santana 2016 (*Ergo*) is the closest published precedent (psychological / social / abstract ontologies) but is too coarse to capture the disciplinary senses of *language* that travel across linguistics, cognitive science, anthropology, philosophy, semiotics, law, and education.

## Working thesis

The label *language* covers a small number of recurrent sense-clusters that travel across fields. Each cluster earns realist scientific standing only where it is stabilised and projectible for a field purpose (Boyd, standard HPC). Confusion arises when the shared label is mistaken for a shared kind, producing slippage between clusters; the most common failure is treating evidence about one cluster as evidence about another (e.g., behavioural-performance evidence used to underwrite cognitive-faculty claims). HPC adds the discipline that Santana's three-criteria pluralism does not: each cluster must pass projectibility and homeostasis tests, and slippage between clusters is a diagnosable failure mode.

## Scope notes

- Primary target: *Language Sciences* (8000-10000 words).
- Engage Santana 2016 (*Ergo*) directly as the closest published precedent. The HPC contribution must do work Santana's three-criteria pluralism does not.
- The brainstorm cluster list (12 entries) needs aggressive consolidation. Likely landing zone: 5-7 clusters that genuinely license different inferences and rely on different stabilizers.
- Per-cluster template: paradigm cases, boundary cases, diagnostics, stabilizers (at the right grain), projection target, defeat conditions, slippage risks.
- Casten et al. 2026 / Pinker tweet is the worked slippage example — verbal-performance phenotype evidence read as evidence about language faculty. See `notes/casten-2026-haqer-as-biocognitive-splitting-test.md` (carried over from the predecessor project, in `archive/Three_purposes_three_HPC_categories_of_language/`).
- The paper should not pretend the cluster taxonomy is closed. New clusters are admissible if they pass projectibility and homeostasis tests.

## Source grounding (LAW)

- HPC theory: cite Boyd directly when introducing the framework, not Brett's prior applications.
- Santana 2016: cite early and generously; acknowledge the structural overlap; show what HPC adds.
- **Brett's HPC book is a load-bearing source for this paper, even if it doesn't end up cited in the final draft.** The book's chapters on categories without essences, projectibility-and-three-checks, grain warnings, social stabilization, and the asymmetric-fraying / conditioning-gain predictions inform the paper's HPC discipline. Read it before drafting the §2 HPC section and the §9 slippage section. If the eventual paper cites a published source rather than the book for a given move, that's fine — but the reasoning should pass through the book first.
- Linguistic examples: cite primary literature for any specific claim about sign languages, writing, animal communication, LLM output, named languages, dialects, creoles, programming languages, or developmental phenotypes.
- Brett's prior papers (`Functions_as_Comparanda`, `Grammaticality_as_Kind_Miller`, `LLMs_as_boundary_phenomena`, `Constructions_as_causal_mesoscales_in_CE_2_0`, `How_to_Study_Boundary_Phenomena`, `Language_as_a_Stack_of_HPC_Kinds`): cite where they supply illustrative material.
- Do not generate linguistic data from memory. Read the source first.

## House style

Brett's house-style rules load automatically via `.claude/rules/` for `.tex`, `.qmd`, and related files. Contractions preferred, ~60-word paragraphs, no em-dashes (commas, parentheses, or `--` for en-dashes), direct verbs, no hackneyed adverbs.

## Attribution discipline

Two existing moves are load-bearing here. Pluralism about the ontology of language is Santana's (2016, *Ergo*); projectibility-for-a-purpose is Boyd's (standard HPC). The paper's contribution is the synthesis: HPC discipline applied to a more granular cluster taxonomy than Santana's three ontologies, plus slippage diagnoses as the methodological payoff. Frame the paper accordingly. Do not present Santana's pluralism or Boyd's projectibility move as the paper's innovation.

## Audience calibration

Primary target is *Language Sciences*. The journal explicitly welcomes work that enlarges the view of language and *languaging*, debates on metatheoretical and epistemological issues, and scrutiny of how the object of language studies is conceived and constructed. Open with a live slippage case (Casten/Pinker is a candidate), not with HPC theory in the abstract. The paper should be readable by sociolinguists and philosophers of linguistics alike.

## Predecessor project

The earlier project, `Three_purposes_three_HPC_categories_of_language`, is now in `archive/`. It accumulated four rounds of review-board feedback over 2026-04-25. The reframe to a pluralist-map paper was prompted by Santana 2016 and the round 1-3 panel's convergence pressure that the previous "field-relative HPC categories" framing was at risk of being read as Santana with HPC vocabulary. The archive contains the round 1-4 reviews, the revised plan, and the initial main.tex draft, all preserved.

## Open decisions (see DECISIONS.md)

- Final cluster taxonomy (consolidation from 12 to ~5-7).
- Length and structure given the venue's word budget.
- Whether the paper takes a position on contested clusters (e.g., language-of-thought) or treats them as inventoried-without-verdict.
- Relationship to the HPC book (stand-alone paper vs candidate chapter).
- Whether to keep the same advisory board (`advisory-board.md` to be created here, or carried over from archive).

---

## Build System (template content from create-paper.sh)

This LaTeX project requires **XeLaTeX** (not pdfLaTeX) due to the Charis SIL font requirement. **Avoid LuaLaTeX** — it tends to run words together in the underlying PDF text layer.

```bash
make              # Full build
make quick        # Single pass
make clean        # Clean artifacts
```

## Citations and BibTeX (LAW)

- Citations and BibTeX entries must NEVER be placeholders.
- Citations must NEVER be generated from training data.
- LLMs MUST verify DOIs and bibliographic data against authoritative sources.
- If you cannot verify a citation, say so. Do not guess.

`references.bib` should be a symlink to the central house-style bibliography; project-specific additions go in `references-local.bib`. The current stub `references.bib` will be replaced when the bibliography is wired up.
