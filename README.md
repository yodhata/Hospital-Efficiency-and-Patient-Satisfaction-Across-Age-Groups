# Hospital Efficiency and Patient Satisfaction Across Age Groups: A Comparative Analysis

## Author

**Yodha Pranata, RN** Data Analyst Enthusiast

[LinkedIn Profile](https://linkedin.com/in/yodha-pranata)

## Project Overview

This project is a comparative analysis focused on hospital operational efficiency and patient satisfaction levels, categorized by age groups (Adults vs. Elderly). The study aims to understand how Length of Stay (LOS), treatment costs, and patient experience correlate to support better managerial decision-making in healthcare facilities.

## Background & Problem Statement

* **Operational Efficiency**: Length of Stay (LOS) and Total Costs directly impact bed occupancy rates, staff workload, and the overall financial health of a hospital.
* **Patient Satisfaction**: A key quality indicator linked to patient loyalty and hospital reputation.
* **Age Gap**: Elderly patients often experience longer LOS and higher costs due to chronic conditions, yet they value empathy and direct care, whereas adults often prioritize speed and digital access.
* **Key Questions**:
1. Is there a significant difference in LOS between adult and elderly patients?
2. How do total treatment costs differ between these two groups?
3. To what extent does reported satisfaction vary by age group?



## Objectives

To analyze the differences in length of stay, treatment costs, and patient satisfaction between adult and elderly groups as a basis for hospital managerial decision-making.

## Data Understanding

* **Source**: Anonymized inpatient data from Kaggle.
* **Timeline**: January 2022 to December 2025.
* **Dataset Size**: 984 records with 15 columns (including Age, Condition, Length_of_Stay, Total_Cost, and Satisfaction).
* **Satisfaction Scale**: 2 to 5.

## Methodology (Data Preprocessing)

1. **Data Cleaning**: No duplicate data or missing values were found.
2. **Outlier Screening**: No significant outliers were detected.
3. **Data Transformation**: Converted admission and discharge dates into *datetime* format for LOS calculation.

## Key Findings & Insights

* **Overall Satisfaction**: The average satisfaction score is 3.6/5 (71.97%), indicating a moderate level of satisfaction.
* **Age Comparison**:
* Adult patients (18–59 years) reported higher satisfaction (3.95) compared to the elderly (3.07).
* The average Length of Stay (LOS) was slightly longer for the elderly (38.49 days) compared to adults (37.11 days).


* **Cost Correlation**: Low satisfaction (score 2) correlates strongly with very high treatment costs (average 14.03K).
* **Statistical Analysis**:
* No significant difference in LOS between groups (p = 0.29).
* Significant differences were found in **Total Cost** (p = 0.01) and **Satisfaction Levels** (p = 0.00).



## Recommendations

* **Implement 4Ms Framework for Elderly**: Focus on *What Matters* (patient goals), *Medication*, *Mentation* (mental health), and *Mobility*.
* **Proactive Discharge Planning**: Start discharge planning on day one to prevent high-cost readmissions.
* **Diagnostic & Laboratory Stewardship**: Audit elderly cases with low satisfaction to identify cost drivers (e.g., redundant tests) and optimize the hospital formulary.
* **Cost Transparency**: Provide pre-procedure cost estimates and daily billing summaries to reduce dissatisfaction caused by "sticker shock."
* **Age-Specific Strategies**:
* **Adults**: Enhance digital service channels (online registration, digital results) to maintain efficiency.
* **Elderly**: Provide administrative assistance, priority queues, and age-friendly physical environments.



---

*This project demonstrates the importance of balancing operational efficiency with quality-driven, patient-centered care.*
