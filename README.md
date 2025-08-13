Project Background

This project provides a comprehensive data analysis of a dental clinic's operations from 2020 to 2025. The clinic's business model is centered on a wide range of services, with orthodontics serving as a critical revenue driver due to its predictable, recurring monthly income. The analysis aims to transform raw data into actionable insights and strategic recommendations for the clinic's partners, focusing on key operational and patient engagement metrics.

Based on the extracted data and the clinic's operational context, this analysis will deliver insights and recommendations across four critical areas:

Patient Retention & Cohort Analysis: Evaluation of patient retention patterns over time, specifically for orthodontic patients, to understand long-term engagement and the financial stability they provide.

Patient Engagement & Segmentation: Creation of a patient segmentation model based on appointment frequency to identify and categorize patients by their level of engagement (Low, Medium, and High).

Appointment & Dropout Analysis: Detailed analysis of the intervals between patient appointments to establish a clear dropout criterion and identify the proportion of patients at risk of abandoning treatment.

Distribution of Patient Visits: Visualization of the distribution of total maintenance appointments per patient to quickly summarize patient engagement levels across the entire clinic's base.

All  Python notebooks used for this analysis are available within this repository.

Data Structure & Initial Checks

The analysis is based on a database that consists of several interconnected tables. While the full structure is extensive, the key dataframes used for this specific analysis are:

ortho_appointments_df: Contains records of appointments specifically for orthodontic maintenance. This was the primary dataset used for cohort and dropout analysis.

ortho_installations_df: Logs the start of orthodontic treatments. This was used to identify patient cohorts and for conversion rate calculations.

total_clients_df: Holds demographic and consultation information for all patients, used to identify the total pool of potential customers.



Executive Summary

The analysis reveals a mixed but actionable picture of the clinic’s operational health. The orthodontic segment stands out as a critical pillar of financial stability, with a resilient patient base that provides consistent, predictable revenue. However, a significant portion of the total patient base falls into a "Low Engagement" category, indicating a potential for churn. This is further supported by a high dropout proportion, suggesting a critical gap between scheduled and actual patient follow-ups. The clinic's success is therefore tied to its ability to leverage its strong orthodontic base while strategically re-engaging less committed patients and optimizing patient flow to reduce abandonment.

<img width="630" height="470" alt="count_by_engagement_level" src="https://github.com/user-attachments/assets/f44d9308-33fd-4f65-9d71-a8737f500d4c" />


<img width="1363" height="989" alt="cohort_heatmap" src="https://github.com/user-attachments/assets/dc5c852c-f67a-44c1-9e73-12aa4c802ba2" />


Insights & Recommendations
1. Patient Retention: A Stable Orthodontic Base
Insight: Our Cohort Analysis revealed that orthodontic patients demonstrate strong long-term retention, providing a predictable and stable stream of recurring revenue. This segment is less susceptible to the market volatility that may affect general procedures.

Recommendation: It is strategically imperative to expand the orthodontic patient base. Invest in targeted digital marketing and lead generation efforts specifically for orthodontic treatments. Emphasize the long-term value and predictable payment plans to attract new patients, ensuring a stable cash flow for the business.

2. Patient Engagement: A Call for Action
Insight: The Patient Engagement analysis revealed a clear segmentation of the patient base. A significant percentage of patients are classified as "Low Engagement" (fewer than 12 appointments), indicating a high risk of churn and a potential missed opportunity for long-term care.

Recommendation: Develop and implement targeted communication campaigns to re-engage the "Low Engagement" patient segment. Use automated follow-ups to remind these patients of the importance of consistent care, schedule their next appointments, and address any potential barriers to their return.

3. Dropout Analysis: A Critical Operational Gap
Insight: The analysis of appointment intervals identified a concerningly high dropout proportion. A large number of patients have not had an appointment in a timeframe that exceeds the average interval, highlighting a gap in patient follow-up and a critical operational inefficiency.

Recommendation: Implement a proactive follow-up system for patients who have surpassed the defined dropout criterion. This could involve automated alerts for staff to contact these patients, and a review of the scheduling process to understand if there are systemic issues contributing to patient disengagement.

Limitations
These are factors that were not (or could not be) fully accounted for, or limitations inherent to the data/analysis that might influence conclusions:

Lack of External Data: The analysis is purely internal to the clinic. It does not incorporate external market dynamics such as local competition, broader economic shifts, or specific industry trends.

Lack of Qualitative Data: While quantitative trends were identified, the analysis does not incorporate qualitative data from patient surveys or staff interviews. This limits a deeper understanding of the "why" behind patient drop-offs, engagement levels, or specific reasons for delays.

About & Topics
This repository features Python scripts for an in-depth data analysis of a dental clinic's operations (2020-2025). It explores various analytical techniques, including cohort analysis, patient segmentation, and distribution analysis, to provide actionable recommendations for business growth and operational efficiency.
