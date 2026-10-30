# Data

## Status

Raw survey responses are **not included** in this public repository to protect participant privacy. This folder documents the dataset structure so the study can be understood and, with appropriately anonymized data, reproduced.

## Dataset Summary

| Item | Detail |
|---|---|
| Source | Structured online questionnaire (Google Forms, email, social media) |
| Respondents | 118 |
| Region | Chennai e-commerce sector |
| Sampling | Convenience sampling |
| Format | Tabular, one row per respondent |
| Tools | Microsoft Excel, Python (Pandas, NumPy) |
| Publication | Aggregated results only |

## Expected Structure

Each row represents one anonymized respondent. Columns correspond to the questionnaire items in [`../docs/questionnaire.md`](../docs/questionnaire.md).

| Column | Type | Description |
|---|---|---|
| `respondent_id` | Integer | Anonymized identifier |
| `age_group` | Categorical | Below 18 / 18-24 / 25-34 / 35-44 / 45-54 / 55+ |
| `gender` | Categorical | Male / Female |
| `education` | Categorical | High school or below / Undergraduate / Postgraduate / Doctorate / Other |
| `income_range` | Categorical | Income bracket or prefer not to disclose |
| `security_factor` | Categorical | Strong authentication / encryption / fraud detection / transparency / support |
| `trusted_gateway` | Categorical | CCAvenue / PayU / Paytm / all equally secure / none |
| `security_concern_frequency` | Ordinal | Frequently / Occasionally / Never |
| `privacy_confidence` | Ordinal | Very high confidence to no confidence |
| `secure_transaction_feature` | Categorical | 2FA / encryption / fraud alerts / confirmations / tokenization |
| `trust_factor` | Categorical | Reputation / security measures / feedback / integration / speed and ease of use |
| `transparency_importance` | Ordinal | Extremely to not important |
| `reputation_influence` | Ordinal | Strong to no influence |
| `ease_of_use_effect` | Ordinal | Very significant to not important |
| `integration_trust` | Ordinal | Significantly higher to preference for independent gateways |
| `encryption_familiarity` | Ordinal | Very familiar to not familiar |
| `fraud_protection_influence` | Ordinal | Significant to no influence |
| `twofa_effectiveness` | Ordinal | Highly effective to very ineffective |
| `data_sharing_comfort` | Ordinal | Always comfortable to never comfortable |
| `security_updates_importance` | Ordinal | Extremely to not important |
| `common_issue` | Categorical | Transaction failure / delay / support / security concern / fees |
| `failure_frequency` | Ordinal | Frequently / Occasionally / Never |
| `dispute_satisfaction` | Ordinal | Very satisfied to very dissatisfied |
| `delay_frequency` | Ordinal | Very frequently / Occasionally / Rarely / Never |
| `support_efficiency` | Ordinal | Highly efficient to very inefficient |
| `usage_frequency` | Ordinal | Daily to never |
| `primary_purpose` | Categorical | Shopping / bills / travel / food / P2P / other |

## How to Reproduce the Analysis

1. Collect responses using the instrument in [`../docs/questionnaire.md`](../docs/questionnaire.md).
2. Encode responses in Microsoft Excel or a Pandas DataFrame.
3. Compute frequency counts and percentages for each item.
4. Compute mean and weighted-average scores for ordinal items.
5. Generate bar and pie charts for each question.
6. Compare the results with the tables in [`../docs/findings.md`](../docs/findings.md).

## Privacy

Only aggregated, non-identifying results should be shared. Never commit raw responses containing personal or sensitive information to a public repository.
