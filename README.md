# literarysource

_Created: 15-02-2022 · Last updated: 11-07-2026_

Study of the **literary sources** (`<ls>` citation abbreviations) referenced in the
Cologne Digital Sanskrit Lexicon (CDSL) dictionaries, and the search for scanned copies
of those works so they can be linked from the display program. Part of the
[sanskrit-lexicon](https://github.com/sanskrit-lexicon) project.

Umbrella tracking issue:
[sanskrit-lexicon/COLOGNE#390](https://github.com/sanskrit-lexicon/COLOGNE/issues/390).

## What is here

Each subdirectory holds the extracted list of works-consulted / source abbreviations for
one dictionary. These are the raw material for building `<ls>` link targets (the
Dictionary-to-Book workflow), not the dictionary text itself.

| Directory | Files | Content |
|---|---|---|
| [`ap90/`](https://github.com/sanskrit-lexicon/literarysource/tree/main/ap90) | [`ap90_ls.tsv`](https://github.com/sanskrit-lexicon/literarysource/blob/main/ap90/ap90_ls.tsv) (191 lines) | Apte 1890 (AP90) source abbreviations |
| [`ben/`](https://github.com/sanskrit-lexicon/literarysource/tree/main/ben) | [`BEN.extracted.ls.entries.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/ben/BEN.extracted.ls.entries.txt) (218 lines), [`tooltip.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/ben/tooltip.txt), [`readme.md`](https://github.com/sanskrit-lexicon/literarysource/blob/main/ben/readme.md) | Benfey (BEN) `<ls>` entries, from Andhrabharati (18 Feb 2022) |
| [`mw/`](https://github.com/sanskrit-lexicon/literarysource/tree/main/mw) | [`mwauth.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/mw/mwauth.txt) (743 lines) | Monier-Williams (MW) authorities list |
| [`mw72/`](https://github.com/sanskrit-lexicon/literarysource/tree/main/mw72) | [`mw72_ls.tsv`](https://github.com/sanskrit-lexicon/literarysource/blob/main/mw72/mw72_ls.tsv) (109 lines) | Monier-Williams 1872 (MW72) works consulted |
| [`pw/`](https://github.com/sanskrit-lexicon/literarysource/tree/main/pw) | [`pwbib.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/pw/pwbib.txt) (791 lines), [`pwbib_input.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/pw/pwbib_input.txt) (844 lines) | Petersburg small dictionary (PW) bibliography |
| [`pwg/`](https://github.com/sanskrit-lexicon/literarysource/tree/main/pwg) | [`pwgbib.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/pwg/pwgbib.txt) (2,681 lines), [`pwgbib_input.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/pwg/pwgbib_input.txt) (2,666 lines), [`lsextract_pwg_06.txt`](https://github.com/sanskrit-lexicon/literarysource/blob/main/pwg/lsextract_pwg_06.txt) (2,704 lines) | Petersburg large dictionary (PWG) bibliography |

Line counts are the current file sizes as of the last-updated date above; re-verify with
`wc -l` before citing.

## Status

As of 11-07-2026, work proceeds per-dictionary through GitHub issues — currently
**3 open, 0 closed**:

| # | Dictionary | Task |
|---|---|---|
| [1](https://github.com/sanskrit-lexicon/literarysource/issues/1) | MW72 | Correct digitized works-consulted list; add scan links |
| [2](https://github.com/sanskrit-lexicon/literarysource/issues/2) | BEN | Extracted `<ls>` entries for review |
| [3](https://github.com/sanskrit-lexicon/literarysource/issues/3) | AP90 | Reconcile `<ls>` entries with Andhrabharati's file |

## Issue conventions

This repository follows the Cologne **tooling-repo** issue taxonomy — one type label, one
severity label, and one milestone per issue. See the
[Cologne tooling runbook](https://github.com/sanskrit-lexicon/csl-observatory/blob/main/runbook/cologne-tooling-runbook.md)
for the full label set and milestone mapping; domain labels here are scoped to source
linking (e.g. `domain:source-mapping`). Cross-repo tool work is tracked on the org
[Tooling Roadmap](https://github.com/orgs/sanskrit-lexicon/projects/9).

## License

Data and documentation are licensed CC-BY-SA-4.0 — see
[`LICENSE`](https://github.com/sanskrit-lexicon/literarysource/blob/main/LICENSE).

_Dr. Mārcis Gasūns_
