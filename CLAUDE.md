# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**literarysource** is a research repository for studying the literary sources (`<ls>` references) cited in various CDSL dictionaries and identifying scanned books that can provide browsable links for those citations. Related to [COLOGNE issue #390](https://github.com/sanskrit-lexicon/COLOGNE/issues/390).

## Architecture

Each subdirectory corresponds to one dictionary and contains authority/bibliography files used to resolve `<ls>` citations:

| Directory | Dictionary |
|---|---|
| `ap90/` | Apte's Sanskrit-English Dictionary (AP90) |
| `ben/` | Benfey Sanskrit-English Dictionary |
| `mw/` | Monier-Williams Sanskrit-English Dictionary (`mwauth.txt`) |
| `mw72/` | Monier-Williams 1872 |
| `pw/` | Böhtlingk Sanskrit-Wörterbuch |
| `pwg/` | Böhtlingk-Roth Großes Sanskrit-Wörterbuch |

### `mwauth.txt` format

The authority file lists literary source abbreviations with their full bibliographic references, used to map `<ls>abbrev.</ls>` tags in dictionary XML to human-readable citations and eventually to scanned-book URLs.

## Dependencies

No scripts — this is a data/research repository. Analysis work is done in the per-dictionary subdirectories.
