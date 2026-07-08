# Maternal social care experience during adolescence and their children’s early health and educational outcomes

This repository contains the R code used in the following study:

Shi D, Jay M, Gilbert R, Vousden N, Mc Grath-Lone L, Harron K. *Maternal social care experience during adolescence and their children’s early health and educational outcomes*.

The analyses were conducted using the [ECHILD](https://www.echild.ac.uk/) (Education and Child Health Insights from Linked Data) resource, a national linked administrative dataset combining health, education, and children's social care records in England.

## Repository structure

### Cohort creation

The `00_build_cohort` directory contains scripts used to construct the analytical cohorts for:

- `birth_outcomes_cohort` – birth outcomes;
- `health_outcomes_age1_cohort` – health outcomes during the first year of life;
- `health_outcomes_age1_5_cohort` – health outcomes between ages 1 and 5 years;
- `educational_outcomes_cohort` – school readiness at age 5.

### Analyses

- `01_descriptive_stats` – scripts used to generate `Table 1`, `Figure 1`, and `Supplementary Figure 3`.
- `02_main_analysis` – scripts used to generate `Table 2` and `Figure 2`.

## Data availability

The raw data are not included in this repository because they contain confidential individual-level administrative records.

All analyses were conducted using the ECHILD database within the Office for National Statistics Secure Research Service. Access to ECHILD data is subject to approval through the ECHILD Data Access Committee. Further information is available on the [ECHILD data access page](https://www.echild.ac.uk/data-access).

## Reproducibility

The scripts in this repository are provided to support transparency and reproducibility of the published analyses. Researchers with approved access to ECHILD data should be able to reproduce the analyses using the code provided.
