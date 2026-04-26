# HANDOFF

Written 2026-04-26 at the close of a long planning session. Project is fully scaffolded; drafting hasn't started.

## Read first, in this order

1. `CLAUDE.md` — Role, Purpose, Working thesis, Scope, Source grounding (incl. HPC book), Attribution, Audience, Open decisions.
2. `PLAN.md` — substantial. Six clusters, five-component §2, five slippage patterns in §9, eleven-section architecture.
3. `DECISIONS.md` — the rationale for the consolidation, the boundary-case resolutions, the panel swap.
4. `STATUS.md` — current state and next action.
5. `advisory-board.md` — the six reviewers (Boyd / Khalidi / Ereshefsky / Santana / Agha / Fitch) with personas updated for this paper's framing.

## Next action

Populate the per-cluster template for the six clusters (`PLAN.md` "Per-cluster template" section):

- **paradigm cases**, **boundary cases**, **diagnostics**, **stabilizers** (at the right grain — micro / meso / macro where applicable), **projection target** (conditional form: "observed P licenses expected Q in unobserved cases"), **defeat conditions**, **slippage risks** (which other clusters this one gets confused with, and what overclaims that produces).

Suggested order:

1. **Capacity** first. The Casten / Pinker slippage example hangs off it and that's the §1 hook.
2. **Communicative practice** second. It carries the most operationalisation-slippage material and the metapragmatic-typification machinery.
3. The remaining four (Idiolect / Population convention / Named sociohistorical object / Abstract formal system) can be done in any order.

After all six are populated, the per-cluster sections (§§3–8) can be drafted from them.

## Things not captured in the planning docs

**Brett's HPC book is load-bearing.** Even if not cited in the final paper, the book's machinery informs §2's HPC discipline and §9's slippage section. Specifically: Chapter 4 (categories without essences), Chapter 7 (projectibility / three checks), Chapter 8 (failure modes / two diagnostics / grain), Chapter 16 (social stabilization / "no conditioning gain, no maintenance claim"), Appendix Predictions (asymmetric fraying / conditioning gain / projection-without-maintenance as defeat). Read these before drafting §2.

**Brett's position on LoT (cluster #10).** "I don't think there is such a thing." The §2 set-aside note should reflect this skepticism but stay neutral enough not to commit the paper to a philosophical position about mental representation it doesn't otherwise earn. Two sentences max.

**Read Santana 2016 directly before drafting §2.** DOI 10.3998/ergo.12405314.0003.019. The engagement has to be substantive, not paraphrased from this handoff or from the intake notes. Santana's three criteria (existence, primacy in linguistic practice, reasonable use of the term) and his two strictures (no isolationism, no agnosticism) need careful engagement; the paper extends his pluralism with HPC discipline, it does not replace it.

**Casten / Pinker as the §1 hook.** See `notes/casten-2026-haqer-slippage-example.md`. The claim is that HAQER / verbal-performance-developmental-phenotype evidence is being read as language-faculty evidence. This is the slippage from Capacity-as-acquisition-development to Capacity-as-faculty (a within-cluster slippage), or arguably the slippage from Capacity to Abstract formal system (cross-cluster slippage). Decide which framing works better for the paper's lead. Source-ground HAQER claims before drafting.

**Advisory board includes Santana.** When running `/review-board` on the eventual draft, the panel will press whether the paper credits him properly and whether HPC adds work over his three-criteria pluralism. The hostile-pluralist axis (Ereshefsky + Santana together) is the live contrast class for this paper.

## Operational state

- Bibliography: `references.bib` is a symlink to the central house-style bib; `references-local.bib` contains the Santana 2016 entry. Add new project-specific entries to `references-local.bib`. Run `/push-bib` at polish time to merge.
- `main.tex` has the standard scaffold (title / author / abstract / 5 TODO sections / acknowledgements / printbibliography). Restructure to the 11-section architecture in `PLAN.md` when drafting begins.
- `AGENTS.md` and `GEMINI.md` are kept in sync with `CLAUDE.md` by a pre-commit hook. Edit only `CLAUDE.md`.
- The previous session's Bash was wedged after the archive `mv`. Fresh session = clean shell.

## Predecessor

Archived at `archive/Three_purposes_three_HPC_categories_of_language/` with full git history. Worth a glance:

- `notes/reviews/2026-04-25-review-board.md` through `-round-4.md` — four rounds of review-board feedback that converged on the reframe.
- `main.tex` — initial drafting attempt under the previous framing ("field-relative HPC categories of LANGUAGE").
- `PLAN.md` — the previous architecture (three categories) with rounds of revision visible in git history.

The predecessor's framing was that *language* across three fields was one HPC category with three projectibility profiles. The round 1-3 review board converged on the disunity-one-level-down problem (each "field-relative category" was itself an umbrella). The Santana 2016 intake then showed that even after addressing that, the paper risked reading as Santana plus HPC vocabulary. Hence the reframe to a pluralist map of senses with HPC discipline.

## Open decisions still pending

See `DECISIONS.md` "Open" section. Most relevant for next session:

- Per-cluster template content (the work above).
- Whether the paper takes a position on contested clusters (LoT mostly handled now; broader semiotic frame mostly handled; methodological-construct mostly handled).
- Relationship to the HPC book (stand-alone paper / candidate chapter / both).
- Final cluster-section ordering once templates are populated.
