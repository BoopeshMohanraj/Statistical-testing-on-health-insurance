# Statistical-testing-on-health-insurance
# Comparative Analysis of Public and Private Health Insurance

This project analyzes public and private health insurance data from 2013 to 2022 in the United States to identify disparities, trends, and correlations. The insights aim to inform better health policy decisions and assist individuals in making informed insurance choices.

---

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Project Goals](#project-goals)
- [Data Preparation](#data-preparation)
- [Visualizations and Insights](#visualizations-and-insights)
- [Statistical Testing](#statistical-testing)
- [Project Results and Conclusions](#project-results-and-conclusions)
- [Major Findings](#major-findings)
- [Lessons Learned](#lessons-learned)
- [Limitations and Future Work](#limitations-and-future-work)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [License](#license)

---

## Introduction

Understanding health insurance disparities and trends is critical for improving access to healthcare. This project uses statistical analysis, hypothesis testing, and visualizations to examine differences in public and private insurance across demographics, geographic locations, and time periods.

---

## Problem Statement

- **Identifying disparities:** Analyze health insurance coverage across demographics, including age, household income, sex, and state.
- **Facilitating informed choices:** Provide actionable insights for consumers to choose between public and private health insurance plans.

---

## Project Goals

1. Visualize state-wise health insurance coverage rates for public and private insurance.
2. Examine premium trends and their impact on enrollment.
3. Evaluate demographic factors influencing insurance choices.
4. Perform gap analysis to identify disparities in insurance coverage.
5. Conduct hypothesis testing to validate observed disparities.
6. Use predictive analytics to forecast future enrollment trends.
7. Provide policy recommendations based on findings.

---

## Data Preparation

### Data Sources
- **Census Bureau**
- **Centers for Disease Control and Prevention (CDC)**
- **KFF.org**
- **Statista**
- **Commonwealth Fund**

### Variables of Interest
1. Demographics: Age, household income, sex, and state.
2. Insurance Status: Public vs. private enrollment.
3. Premiums and Coverage Options.
4. Geographic and Temporal Data: Year-over-year changes and state-wise trends.

---

## Visualizations and Insights

### State-wise Coverage
**ADD IMAGE**: Include maps showing average enrollment in public and private insurance across states.

- **Insight:** North Dakota leads in private insurance enrollment, while New Mexico has the highest public insurance coverage.

### Uninsured Analysis
**ADD IMAGE**: Boxplots for uninsured individuals across regions (West, Midwest, South, Northeast).

- **Insight:** Alaska (West) and Indiana (Midwest) had the highest uninsured rates.

### Gender-based Trends
**ADD IMAGE**: Line graphs for male and female enrollment in public vs. private insurance.

- **Insight:** Public health insurance enrollment increased slightly post-2020, while private insurance saw a decline.

### Correlation Analysis
**ADD IMAGE**: Correlation plots for income-to-poverty ratio vs. enrollment in public and private insurance.

- **Insight:** Below 100% poverty ratio has:
  - **High positive correlation (r=0.846)** with public insurance.
  - **Weak positive correlation (r=0.108)** with private insurance.

### Predictive Analytics
**ADD IMAGE**: Trendline forecasting enrollment in public and private health insurance.

- **Insight:** Public insurance enrollment is expected to rise significantly in the next decade.

---

## Statistical Testing

1. **COVID-19 Impact on Public Insurance for Individuals Under 19**  
   - Null Hypothesis: No significant increase in enrollment.
   - Result: Failed to reject null hypothesis (p-value = 0.508).

2. **Correlation Between Premiums and Enrollment**
   - **Private Insurance:** Weak positive correlation (r = 0.041).
   - **Public Insurance:** Strong positive correlation (r = 0.967).

---

## Project Results and Conclusions

### Results
- **Public insurance enrollment:** Positively correlated with rising premiums and economic conditions.
- **Private insurance enrollment:** Shows little correlation with rising premiums.
- **State-wise trends:** Reflect economic and policy differences.

**ADD IMAGE**: Include maps for state-wise average enrollment in public and private insurance.

- **Gender trends:** Public insurance saw slight increases post-2020, while private insurance declined.

**ADD IMAGE**: Line graphs for male vs. female enrollment trends.

- **Correlation analysis:** Income-to-poverty ratio below 100% is highly correlated with public insurance enrollment.

**ADD IMAGE**: Correlation plots for income-to-poverty ratio vs. public/private enrollment.

- **Future trends:** Enrollment in public insurance is forecasted to rise significantly over the next decade.

**ADD IMAGE**: Trendline forecasting for public and private health insurance enrollment.

### Conclusions
- Public insurance serves as a critical safety net during economic downturns.
- Private insurance is less affected by economic variables due to employer-based coverage.

**ADD IMAGE**: Highlight visual trends or summary charts related to conclusions.

---

## Major Findings

1. No significant pandemic-related increase in public insurance enrollment for individuals under 19.
2. Rising premiums did not significantly reduce private insurance enrollment.
3. Higher premiums correlated with increased public insurance enrollment.

---

## Lessons Learned

- Insurance choices are influenced by factors beyond cost, such as public health emergencies.
- Accurate statistical analyses require proper alignment with data characteristics.
- Predictive analytics provide valuable insights but must be validated against real-world outcomes.

---

## Limitations and Future Work

### Limitations
1. Reliance on secondary data may introduce inaccuracies.
2. Lack of consumer satisfaction or insurer quality metrics.
3. Observational analysis limits causal inference.

### Future Work
1. Investigate causal relationships in health insurance trends.
2. Incorporate consumer satisfaction data for holistic analysis.
3. Implement a risk assessment framework to guide plan selection.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
