# Returns to Secondary Schooling: Evidence from Botswana's 1996 Education Reform

STAT 5200 final project, University of Pennsylvania, Fall 2026 — Yuzhang Liu.

This project estimates the causal effect of secondary schooling on employment and labor force participation. It uses Botswana's 1996 reform, which expanded access to grade 10, as an instrument for years of schooling (cohorts born after 1980 were exposed).

## Data

Botswana 2001 and 2011 census samples from [IPUMS International](https://international.ipums.org). Data are not included in this repo.

*Status: IPUMS account application is under review. This section will be updated once access is approved.*

## Method

OLS and 2SLS, with the reform cohort indicator as the instrument, estimated separately for men and women.

## Structure

```
data/     # raw and processed data (not tracked)
code/     # analysis scripts
output/   # tables and figures
report/   # LaTeX report
```

## Related

- Group replication: <https://github.com/yuzliu1222/STAT5200Replication>
- Ludwig, J. O., et al. (2021). Causal effect of children's secondary education on parental health outcomes. *BMJ Open*, 11, e043247.
