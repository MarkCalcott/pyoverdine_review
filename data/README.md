# Pyoverdines

A list of manually curated pyoverdines in which pyoverdine structures have been checked against the corresponding papers. The data is a compilation from existing lists and manual searches.

## File overview

| File                            | Description                               |
| ------------------------------- | ----------------------------------------- |
| `pyoverdine_peptide_chains.csv` | One row per pyoverdine peptide chain      |
| `references.csv`                 | Full citations for the `reference` column |

## Column descriptions

| Column      | Type                   | Description                                                | Example                      |
| ----------- | ---------------------- | ---------------------------------------------------------- | ---------------------------- |
| `organism`  | string                 | Full strain name as reported in the source                 | `P. fluorescens 1.3`         |
| `species`   | string                 | Producing species as reported in the source                | `P. fluorescens`             |
| `strain`    | string                 | Strain as reported in the source                           | `1.3`                        |
| `sidechain`    | string                 | Acyl sidechain as reported in the source. Multiple sidechains are separated by a `\|`                           | `Suc`                        |
| `chromophore`    | string                 | Chromophore as reported in the source. Multiple chromophores are separated by a `\|`                           | `Pyoverdine`                        |
| `peptide`   | string                 | Amino acid sequence of the peptide chain, N- to C-terminus | `Ala-Lys-Gly-Gly-OH-Asp-...` |
| `group`     | integer                | Grouping according to paper                               | `1`                          |
| `class`     | string (Roman numeral) | Classification according to paper                          | `II`                         |
| `reference` | integer                | ID of the source publication; see `references.csv`         | `3`                          |

## Peptide notation

See paper for nomenclature.