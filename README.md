# 🧪 A/B Testing Simulation & Statistical Analysis

## 📌 Business Problem

Companies run A/B tests every day — new button colours, pricing pages,
email subject lines, checkout flows. But most teams make one critical
mistake: they call a winner too early, before the results are statistically
meaningful.

This project simulates a real-world A/B test from scratch, applies
proper statistical analysis, and demonstrates how to make the right
call — and avoid the wrong one.

---

## 🎯 Objectives

- Design a statistically valid A/B experiment with correct sample sizing
- Simulate conversion data for Control (A) and Treatment (B) groups
- Run hypothesis testing to determine if results are significant
- Visualise the distribution of outcomes and confidence intervals
- Interpret results the way a business stakeholder actually needs to hear them

---

## 🛠 Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core analysis |
| NumPy | Data simulation |
| Pandas | Data manipulation |
| SciPy | Statistical testing (t-test, chi-square) |
| Matplotlib / Seaborn | Visualisations |
| Jupyter Notebook | Presentation of findings |

---

## 🧠 Concepts Applied

- **Null vs Alternative Hypothesis** — defining what we're testing
- **Statistical Power & Sample Size** — how many users do we need?
- **p-value Interpretation** — what it actually means (and what it doesn't)
- **Confidence Intervals** — showing the range of likely true effects
- **Type I & Type II Errors** — false positives vs false negatives
- **Chi-Square Test** — for conversion rate comparison (proportions)
- **Two-sample t-test** — for continuous metric comparison (revenue, time)

---

## 📊 Experiment Scenario

> **Scenario:** An e-commerce company tests a redesigned checkout button.
> The hypothesis is that the new design increases the conversion rate.

| Parameter | Value |
|-----------|-------|
| Metric | Conversion Rate |
| Control Baseline Rate | 10% |
| Minimum Detectable Effect | 2% lift |
| Statistical Significance | 95% (α = 0.05) |
| Statistical Power | 80% (β = 0.20) |
| Test Duration | 14 days |
| Total Sample Size | ~3,800 per group |

---

## 📁 Project Structure
```
ab-testing-python/
│
├── notebooks/
│   └── ab_test_analysis.ipynb     # Full analysis walkthrough
│
├── src/
│   └── ab_test_simulator.py       # Reusable simulation functions
│
├── outputs/
│   ├── conversion_distribution.png
│   ├── confidence_interval_plot.png
│   └── results_summary.png
│
└── README.md
```

---

## 📈 Key Results

| Group | Users | Conversions | Conversion Rate |
|-------|-------|-------------|-----------------|
| Control (A) | 3,842 | 387 | 10.07% |
| Treatment (B) | 3,842 | 461 | 12.00% |

- **Observed Lift:** +1.93%
- **p-value:** 0.0031
- **Result:** ✅ Statistically significant at 95% confidence

**Business Recommendation:**
> Roll out the new checkout button. The treatment group showed a
> statistically significant 1.93% lift in conversion rate (p = 0.0031).
> At current traffic volumes, this translates to an estimated 
> 180+ additional conversions per month.

---

## 📉 Visualisations

### Conversion Rate Comparison


### Confidence Interval Plot


### p-value Distribution


---

## ⚠️ Common A/B Testing Mistakes This Project Addresses

- **Peeking problem** — stopping the test early when you see a lift
- **Underpowered tests** — not having enough sample size to detect real effects
- **Multiple testing** — running too many variants inflates false positive rate
- **Ignoring practical significance** — a result can be statistically significant
  but too small to matter for the business


---

## 🔗 Connect

**Amreen Shaikh** — Data Analyst | SQL · Python · Power BI · Tableau

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/amreen-shaikh-787bab1ba/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-brightgreen)](https://amreenshaikh2224.github.io/portfolio/)

---

*This project is part of my Data Analyst portfolio demonstrating
applied statistics, experimental design, and business-oriented analysis.*
