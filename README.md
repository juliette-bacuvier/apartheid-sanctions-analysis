# Did Anti-Apartheid Sanctions Work?
### Causal Analysis of US Sanctions on South Africa (1986-1991)

[![License: MIT] (https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---
## Overview

**Research Question:** Did US anti-apartheid sanctions (1986-1991) significantly reduce bilateral trade between the US and South Africa?

**Key Finding:**

**Methods:** Difference-in-difference estimation with country-pair and year fixed effects, pre-trend validation, and multiple robustness checks.

**Policy Relevance:** This analysis provides empirical evidence on when economic sanctions can effectively achieve foreigh policy objectives, informing debates about sanctions effectiveness in contemporary conflicts.

---
## Why This Matters

Economic sanctions are a common tool of statecraft, yet their effectiveness remains contested. This project contributes to the sanctions literature by:
1. Providing causal estimates (not just correlation) using state-of-the-art methods
2. Testing parallel trends assumption (often skipped in policy analysis)
3. Demonstrating when unilateral sanctions can achieve measurable economic impact
4. Informing current debates about sanctions policy

---
## Key Results

---
## Methodology

**Design:** Difference-in-Difference (DiD)
- ***Treatment Group:*** US --> South Africa trade flows
- ***Control Group:*** Non-sanctioning countries --> South Africa
- ***Treatment Date:*** October 2, 1986 (comprehensive Anti-Apartheid Act)

**Specification:**

**Identification Assumption:** Parallel trends (validated via event study)

---
## Data Sources

---
## Reproducibility

---
## Repository Structure
```
apartheid-sanctions-analysis/
    README.md             <-- You are here
    data/
        README.md/        <-- Data documention
        raw/              <-- Source data
    notebooks/
        analysis.R        <-- Full analysis walkthrough
    src/
        01_data_cleaning.R
        02_analysis.R
        03_visualitions.R
    results/
        figures/          <-- All plots
        policy_brief.pdf  <-- 2-page summary
    requirements.txt
```

---
## Limitations

This analysis does not:
- Capture trade diversion (increased trade with non-sanctioning countries)
- Account for informal/smuggled trade
- Isolate sanctions from other factors (e.g. internal conflict, commodity prices)
- Prove causality of apartheid's end (sanctions were one of many factors)

**Future extensions:**

---
## References

---
## License

MIT License - see [LICENSE](LICENSE) for details.

---
## Author

**Juliette Bacuvier** | Data Science for Policy & Development | Wellesley College '26

juliette.bacuvier@gmail.com

juliette-bacuvier.github.io

---
## Acknowledgments

- Data sources: IMF, World Bank
- Course context: POL3 221, ECON 101, ECON 102, STAT 318
