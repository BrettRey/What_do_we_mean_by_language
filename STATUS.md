# STATUS

**Last updated:** 2026-04-27
**State:** Preprint posted to LingBuzz (`lingbuzz/009947`) and PhilPapers (`https://philpapers.org/rec/REYWDW`). Full draft built, revised through three review-board rounds, source-grounded, with §9 subsections and Figure 1 in situ. Cluster consolidation locked at six; three boundary cases resolved. **All six per-cluster templates populated** at `notes/cluster-template-*.md`:

- Capacity (5 sub-axes): faculty/processing-architecture; broad-faculty; developmental-acquisition; comparative-biology/vocal-learning; impairment-phenotype.
- Communicative practice (5 sub-axes): speech-act/illocutionary-force; interactional/situational; communicative competence/appropriateness; metapragmatic typification/enregisterment; modality (cross-cutting).
- Idiolect / I-language (3 sub-axes): I-language Chomsky psychological-conception; idiolect Devitt linguistic-conception; empirical individual variation.
- Population-level convention (3 sub-axes): coordination convention Lewis; speech-community variables Labov/Tagliamonte; stylistic/indexical practice Eckert.
- Named sociohistorical object (3 sub-axes): institutional artefact; identity-marker / index of belonging; descended kind / sociohistorical lineage.
- Abstract formal system (4 sub-axes): formal-language theory Chomsky-hierarchy; formal semantics Montague; mathematical-Platonist Katz; computational/NLP working usage.

Source-grounding pass complete (Santana 2016 + HPC book ch 4/7/8/16 + Predictions appendix + Casten 2026 + HCF/PJ/FHC/JP exchange + Hymes 1992 + Agha 2005 + Devitt 2008 + Eckert 2008 + Silverstein 2003 + Pennycook 2010 + Jäger & Rogers 2012). Synthesis at `notes/source-grounding-summary.md`. Bib entries added to `references-local.bib`.

### 2026-04-27 Session Notes

- Draft is now a complete paper with abstract, §1 Casten/Pinker hook, §2 Santana + HPC discipline, §§3-8 map elements, §9 slippage/bridge principles, §10 umbrella label, acknowledgements, and references.
- Reviewer-board synthesis drove revisions to Table 1, perturbation-coupling operationalization, the social-HPC projectibility paragraph, Pinker broad/narrow charity, and Whorfian bridges as positive licensed traversals.
- Table 1 is now non-floating and appears in situ in §2 with caption and table kept together via `\captionof{table}` inside a compact minipage.
- Source-grounding audit fixes completed: softened the vocal-learning regulatory claim; narrowed Table 1 and the Cantonese case to supported claims; added verified local bib entries for Makoni & Pennycook 2006, HK Census 2021 main results, Lee & Leung 2012, and Statistics Canada 2022.
- Notes created for grammaticality-kind-schema compatibility and email drafts to James and Carlos Santana; these were included in commit `27852b2`.
- `notes/preprint-posting-info.md` was created after the push with copy-paste metadata for LingBuzz and PhilArchive. It remains uncommitted as of shutdown.
- Current untracked files: `.agent/slippage-page-12.png`, `.agent/slippage-page-13.png`, `main.pdf`, and `notes/preprint-posting-info.md`.
- Checks run during the session: `../../.house-style/check-style.py main.tex` clean; Biber + XeLaTeX clean after citation additions; table placement verified with `pdftotext` pages 4-5.

**Next action:** Decide whether to commit `notes/preprint-posting-info.md` and/or keep `main.pdf` untracked for local posting. If posting the preprint, use the author-manuscript PDF and the metadata in `notes/preprint-posting-info.md`; do not upload a publisher-formatted file. If editing further, the likely next pass is final compression/submission formatting rather than more argument expansion.

**Blocker:** None.
