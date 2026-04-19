# Dataset Overview & Scope Validation

## Dataset Description
The dataset contains customer-level records for a subscription-based service.
Each row represents an individual customer, and each column captures a specific
attribute related to demographics, service usage, support interactions, payment
behavior, subscription terms, or total spend.

The dataset is treated as a snapshot of customer behavior rather than a complete
customer lifecycle history.

## Column Summary
The dataset includes fields such as:
- CustomerID: Unique identifier for each customer
- Age: Customer age
- Gender: Customer-reported gender
- Tenure: Duration of customer relationship (in months)
- Usage Frequency: Frequency of service usage
- Support Calls: Number of support interactions
- Payment Delay: Delays observed in payment behavior
- Subscription Type: Type of subscription plan
- Contract Length: Duration of the contract
- Total Spend: Aggregate amount spent by the customer

## Assumptions
The following assumptions guide this analysis:
- All records represent active or recently active customers
- Higher support calls and payment delays may indicate dissatisfaction or risk
- Usage frequency and tenure reflect customer engagement indirectly
- The snapshot is assumed to be representative of broader customer behavior

## Limitations
This dataset has several limitations:
- No explicit churn outcome is provided
- No timestamped behavioral history is available
- Causality cannot be established from observed relationships
- External factors (pricing changes, competition, promotions) are not captured

## Analytical Implications
Given these constraints, the analysis will focus on:
- Descriptive patterns and segmentation
- Identifying risk indicators rather than predicting churn
- Supporting strategic decisions rather than operational automation
