# Structural Macro-Demographics: Reassessing Japan’s Population Trajectory

An open-source data repository and analytical framework dedicated to modeling the structural economic and labor-market drivers of Japan's accelerated population decline. 

Rather than treating demographic contraction as a byproduct of personal preferences or isolated biological factors, this repository tracks how systemic corporate labor practices, non-regular employment models, and structural time deficits interact to suppress marriage and birth metrics.

---

## 📊 The Core Hypothesis
Traditional demographic policy paradigms rely heavily on **fiscal interventionism** (direct child-rearing subsidies, cash distributions, and municipal cash frameworks). This model demonstrates that **subsidizing the cost of children yields diminishing returns if the structural work culture deprives young adults of the economic security and personal time required to build a household.** 

By adjusting specific, regulatory labor levers—such as shift intervals, fixed overtime compensation boundaries, and contract security—policymakers can alter the macro-demographic curve at a fraction of the cost of long-term treasury subsidies.

---

## 📈 Key Empirical Benchmarks (MHLW Definitive Data)

This framework operates on the latest official datasets released by Japan's Ministry of Health, Labour and Welfare (MHLW). The numbers prove a stark structural acceleration:

*   **Annual Live Births:** **671,236** (An all-time record low marking the 10th consecutive year of contraction).
*   **Total Fertility Rate (TFR):** **1.14** (The lowest national reading recorded since 1947).
*   **Tokyo Prefecture TFR:** **0.96** (Ground zero of the labor opportunity-cost trap; first prefecture to sustain a sub-1.0 fertility index).
*   **The 15-Year Baseline Shock:** The National Institute of Population and Social Security Research (IPSS) medium-variant projection calculated that annual births would not compress into the 670,000 threshold until the **year 2040**. The reality shows that the structural demographic contraction is running **15 years ahead of schedule**.

---

## 📂 Repository Architecture

```text
japan-demographic-analysis/
│
├── README.md                          <-- Executive summary and thesis overview
├── data/
│   ├── raw_mhlw_stats_2025.csv        <-- Cleaned primary MHLW vital statistics
│   └── regional_labor_split.csv       <-- Haken vs. Regular employment ratios by prefecture
│
├── analysis/
│   ├── economic_barriers.py           <-- Models marriage-rate suppression against non-regular employment
│   └── subsidy_diminishing_returns.py <-- Simulates the marginal utility of cash payouts vs. time availability
│
├── output/
│   └── labor_reform_brief.pdf         <-- High-quality policy brief compiled for diplomatic submission
│
└── simulation/
    └── interactive_app.json           <-- Policy simulation mapping labor regulation variables to long-term TFR
