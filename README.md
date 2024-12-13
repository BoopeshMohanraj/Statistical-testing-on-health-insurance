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
Map showing average enrollment in public and private insurance across states.
![image](https://github.com/user-attachments/assets/b13636d5-0f88-4ccd-8488-6377cc9498b8)
![image](https://github.com/user-attachments/assets/811b7271-50f3-4c3a-9c58-26ddc0b25e36)

- **Insight:** North Dakota leads in private insurance enrollment, while New Mexico has the highest public insurance coverage.

### Uninsured Analysis
Box plots for uninsured individuals across regions (West, Midwest, South, Northeast).
![image](https://github.com/user-attachments/assets/d291fee2-823a-43c0-a5b9-7888405e498d)
![image](https://github.com/user-attachments/assets/754960cc-250d-470b-b458-98fada21b93d)

- **Insight:** Alaska (West) and Indiana (Midwest) had the highest uninsured rates.

### Gender-based Trends
Line graphs for male and female enrollment trends in public vs. private insurance.
![image](https://github.com/user-attachments/assets/c412419a-0fbe-44b3-8c1c-00d350667cc0)

- **Insight:** Public health insurance enrollment increased slightly post-2020, while private insurance saw a decline.

### Correlation Analysis
Scatter plot showing correlations between income-to-poverty ratio and public/private insurance enrollment.
![image](https://github.com/user-attachments/assets/d62238c9-069f-4a6e-baab-6b8416743fda)
![image](https://github.com/user-attachments/assets/2503aa9b-bb99-4230-bc2e-2740fbb724ab)
![image](https://github.com/user-attachments/assets/81c00d0f-991d-49a0-9cfa-7bf47106a8f2)

- **Insight:** Income-to-poverty ratio below 100% is highly correlated with public insurance enrollment.

### Predictive Analytics
Trendline forecasting enrollment in public and private health insurance
![image](https://github.com/user-attachments/assets/55589760-ac38-4530-95f1-8cb04126fdf9)

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
![image](https://github.com/user-attachments/assets/b6197aa0-097a-44fb-8461-374febb02818)
![image](https://github.com/user-attachments/assets/634abf5e-8c70-4875-82b0-b2a2b7e0c69b)

- **Public insurance enrollment:** Positively correlated with rising premiums and economic conditions.
- **Private insurance enrollment:** Shows little correlation with rising premiums.
- **State-wise trends:** Reflect economic and policy differences.
- **Gender trends:** Public insurance saw slight increases post-2020, while private insurance declined.
- **Correlation analysis:** Income-to-poverty ratio below 100% is highly correlated with public insurance enrollment.
- **Future trends:** Enrollment in public insurance is forecasted to rise significantly over the next decade.

### Conclusions
- Public insurance serves as a critical safety net during economic downturns.
- Private insurance is less affected by economic variables due to employer-based coverage.

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
