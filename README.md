# Data for: Linking EU Emissions Trading System account holders to Legal Entity Identifiers: Register-number matching precision and its pitfalls

This repository is a data-only copy of the dataset "Data for: Linking EU Emissions Trading System account holders to Legal Entity Identifiers: Register-number matching precision and its pitfalls" by Anna Lehtinen, deposited on Zenodo: https://doi.org/10.5281/zenodo.23144452 . Every file here is byte-identical to its copy in the Zenodo record; the SHA-256 of each file is listed in `MIRROR_MANIFEST.json`. The paper is a preprint on Preprints.org; its DOI is added here once it is posted.

## About the paper

Linking EU Emissions Trading System account holders to Legal Entity Identifiers (LEIs) lets emissions be read at the level of the legal entity and its parent, and users of such a crosswalk need to know how often a match is wrong. However, a free gold standard made of holders that two matching methods both link need not contain the rows a crosswalk delivers. In this study, we matched account holders to GLEIF records by national business register number and, separately, by declared LEI, then withdrew the crosswalk because European Commission datasets such as JRC-EU ETS-FIRMS already link these holders to firms, though through Orbis identifiers rather than LEIs. Our analysis reveals that against the declared LEI, on the 1,837 holders matched both ways, the first register-number candidate has a precision of 0.9695. This figure was first presented as the precision of the delivered register-number links, yet because labels were assigned by priority, none of those links is in the gold standard. Furthermore, re-weighting per-country precision to those links' country mix, adjusting for country alone, gives 0.9533 to 0.9619 across the three smallest-cell floors we report, so on point estimates the presented figure overstates their accuracy. We provide checks for such gold standards, starting with which delivered label the gold rows carry. Precision for holders without a declared LEI, the population no free gold standard covers, still needs hand-adjudicated matches.

## Files

| file | bytes |
|---|---|
| crosswalk_paths.csv | 820,846 |
| gold_standard_scores.csv | 47,914 |
| precision.json | 2,659 |
| recompute_dpo01.json | 737 |
| reconciliation.json | 301 |

## Not in this repository

2 file(s) of the supplement are code or logs; they are in the Zenodo record only (listed in `MIRROR_MANIFEST.json`).

## How to cite

Cite the data: Anna Lehtinen (2026). Data for: Linking EU Emissions Trading System account holders to Legal Entity Identifiers: Register-number matching precision and its pitfalls [Data set]. Zenodo. https://doi.org/10.5281/zenodo.23144452 . `CITATION.cff` gives the citation (GitHub shows it under "Cite this repository").

## Licence

Creative Commons Attribution 4.0 International (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/ . Reduced tables derived from the EU Transaction Log via euets.info (CC-BY-4.0; attribution to euets.info and to European Commission DG CLIMA) and from GLEIF records (CC0-1.0). Names and identifiers removed.
