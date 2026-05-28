# India Job Market Visualizer

Interactive treemap of India's ~616 million workforce, by industry (NIC) and occupation (NCO). Single static HTML + D3, no build step.

**Live:** https://ramankharchee.github.io/india-jobs-visualizer/

## What's verified vs estimated

Each tooltip row carries a source badge:

| Badge | Meaning |
|---|---|
| **PLFS** | Direct from PLFS 2023-24 Annual Report (NSO/MoSPI) |
| **PLFS÷** | PLFS aggregate (e.g., NCO Division wage) applied uniformly to sub-cell |
| **est** | Author estimate (no PLFS source) |

### PLFS-verified
- Industry broad-division shares + sex splits — Statement 7
- NCO occupation 2-digit shares + sex splits — Table 25 (Appendix A)
- Average regular wage/salaried earnings by NCO Division — Table 50
- Headline indicators (LFPR / WPR / UR) — PLFS Monthly Bulletin April 2026

### Estimates (clearly flagged)
- Growth outlook (%/year) — from PLFS YoY share shifts + sector trend reading
- Digital AI Exposure (0–10) — hand-scored per [karpathy/jobs](https://github.com/karpathy/jobs) rubric
- Formal-sector share per cell
- Sub-sector splits within industry divisions

## Sources

- [PLFS Annual Report 2023–24 (full PDF)](https://mospi.gov.in/sites/default/files/publication_reports/AnnualReport_PLFS2023-24L2.pdf)
- [PLFS Monthly Bulletin April 2026 (PIB)](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2261386)
- [PLFS Annual Report 2025 (PIB)](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2246009)
- Inspiration: [karpathy/jobs](https://github.com/karpathy/jobs)
