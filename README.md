# pancancer_pleiotropy
This README file accompanies the following 17 files that contain GWAS summary statistics for 17 cancers based on a meta-analysis of the UK Biobank and GERA cohorts.

**A description of how these summary statistics were generated and applied to investigate heritability and pan-cancer pleiotropy can be found [here](https://www.biorxiv.org/content/10.1101/635367v2.full):**

Rashkin et al., *Pan-Cancer Study Detects Novel Genetic Risk Variants and Shared Genetic Basis in Two Large Cohorts*, bioRxiv 2019

Columns for each of the files listed above are as follows
| Column Name | Description |
| --- | ---------- |
| CHR | chromosome |
| BP | basepair position in hg19/build 37 |
| uniqID | variant name |
| A1 | effect allele |
| A2 | other allele |
| N | number of studies (N=1 for variants in UKB or GERA only) |
| P | p-value (fixed effects meta-analysis) |
| P_random | p-value (random effects meta-analysis) |
| OR | odds ratio (fixed effects) |
| OR_random | odds ratio (random effects) |
| Q | p-value for Cochran’s Q heterogeneity test |
| I | I^2 heterogeneity index (0-100) |
| ID | variant name (rsID) |
| totN | sample size |
