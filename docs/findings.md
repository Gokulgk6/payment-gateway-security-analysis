# Findings and Interpretation

This document summarizes the themes identified from the 118 responses. Individual response-level figures are not published here; the analysis was performed in Microsoft Excel and the results are described qualitatively.

## 1. Security Perception Drives Gateway Choice

Respondents associated security with the gateway brand and with visible security cues. Perceived security and privacy were recurring factors in gateway preference, often weighted alongside convenience.

**Implication:** security is part of the product experience, not just a backend control.

## 2. Uneven 2FA Awareness and Adoption

Awareness of two-factor authentication was not uniform. Some users actively enabled it; others were unaware it existed or found it inconvenient. Stronger authentication — especially biometric verification — was widely treated as a signal of trustworthiness.

**Implication:** gateways should make 2FA easy to discover, enable, and understand.

## 3. Privacy and Encryption Concerns Affect Trust

Concerns about how payment data is encrypted and handled directly influenced confidence. Users who were unsure about data handling reported lower trust.

**Implication:** transparent communication about encryption and data practices can improve trust.

## 4. Friction Erodes Trust

Transaction latency and authentication failures were linked to reduced perceived reliability. Repeated friction appears to lower overall trust in the gateway and, by extension, the payment infrastructure.

**Implication:** reliability engineering and graceful failure handling are security-and-trust concerns.

## 5. Trust Extends to the Infrastructure

Users did not evaluate a single transaction in isolation. Their trust (or distrust) carried over to the gateway and the broader payment ecosystem.

**Implication:** platform-level transparency and consistent controls matter.

## Cross-Cutting Observations

| Theme | Direction observed |
|---|---|
| 2FA awareness | Mixed; adoption below awareness |
| Biometric authentication | Positive effect on trust |
| Encryption understanding | Low; correlated with lower trust |
| Privacy concern | High; influences gateway preference |
| Latency / failures | Negative effect on trust |
| Security cues (HTTPS, trust seals) | Noticed by a subset of users |

## Recommendations

1. **Strengthen authentication** — expand 2FA and biometric verification for high-value transactions.
2. **Adopt tokenization** — reduce exposure of sensitive card data.
3. **Deploy AI-based fraud detection** — detect anomalous transaction patterns in real time.
4. **Improve transparency** — communicate encryption and data-handling practices clearly.
5. **Align with compliance standards** — follow global security and identity frameworks.
6. **Reduce friction** — address avoidable authentication failures and latency.

## Threats to Validity

- Convenience sample; results are exploratory.
- Self-reported perceptions may not match measured security.
- Social-desirability bias may affect security-related answers.
- Cross-sectional design cannot establish causality.
