# Data Cleaning Strategy

## Objective
Define how the dataset will be cleaned and prepared for exploratory analysis
while preserving transparency and avoiding unnecessary transformations.

## Planned Cleaning Actions
- Identify missing or null values in key columns
- Check for inconsistent categorical labels (e.g., subscription types)
- Review extreme or implausible values in numeric fields
- Standardize column formats where required

## What Will NOT Be Done
- No synthetic data generation
- No imputation that alters semantic meaning
- No removal of rows unless clearly invalid

## Rationale
Cleaning decisions are guided by interpretability and decision relevance,
not by optimization for predictive performance.

## Constraints
- Cleaning will be performed using non-Python tools (spreadsheets / SQL)
- All cleaning steps will be explicitly documented
