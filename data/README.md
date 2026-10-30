# Data

## Status

Raw survey responses are **not included** in this public repository to protect participant privacy. This folder documents the dataset structure so the analysis can be understood and reproduced with appropriately anonymized data.

## Dataset Summary

| Item | Detail |
|---|---|
| Source | Structured security questionnaire |
| Respondents | 118 |
| Format | Tabular (one row per respondent) |
| Tool | Microsoft Excel |
| Publication | Aggregated / summarized only |

## Expected Structure

| Column | Type | Description |
|---|---|---|
| `respondent_id` | Integer | Anonymized identifier |
| `age_group` | Categorical | Age bracket |
| `occupation` | Categorical | Occupation group |
| `gateway_used` | Categorical | Paytm / PayU / CCAvenue / multiple |
| `gateway_primary` | Categorical | Most-used gateway |
| `twofa_aware` | Ordinal | 1–5 awareness |
| `twofa_enabled` | Binary | Yes / No |
| `biometric_trust` | Ordinal | 1–5 |
| `encryption_understanding` | Ordinal | 1–5 |
| `privacy_concern` | Ordinal | 1–5 |
| `latency_frequency` | Ordinal | 1–5 |
| `auth_failure_frequency` | Ordinal | 1–5 |
| `trust_paytm` | Ordinal | 1–5 |
| `trust_payu` | Ordinal | 1–5 |
| `trust_ccaverage` | Ordinal | 1–5 |
| `fraud_experience` | Binary | Yes / No |
| `open_feedback` | Text | Free-text suggestions (anonymized) |

## How to Reproduce the Analysis

1. Collect responses using the questionnaire outline in [`../docs/questionnaire.md`](../docs/questionnaire.md).
2. Clean and encode responses in Excel.
3. Compute frequencies, percentages, and cross-tabulations for each variable.
4. Build per-gateway comparison charts for trust, privacy, and reliability.
5. Summarize themes using the structure in [`../docs/findings.md`](../docs/findings.md).

## Privacy

Only aggregated, non-identifying results should be shared. Never commit raw responses containing personal or sensitive information to a public repository.
