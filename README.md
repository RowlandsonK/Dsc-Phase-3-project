#Phase 3 Project

## Project Overview

In this project, I leveraged a dataset from Kaggle that focuses on SyriaTel, a telecommunications company. Following the OSEMN data science process (Obtain, Scrub, Explore, Model, and iNterpret), I demonstrated my proficiency in data manipulation, exploration, modeling, and insights extraction. The primary objective was to identify the reasons behind customer churn and provide actionable insights to aid SyriaTel's business strategy. 



## EDA

During the exploratory phase, I uncovered essential insights from the data. Notably, I observed that a significant proportion of customers, approximately 85%, remained loyal, while the remaining 14% were classified as churned customers. Although the number of churned customers was smaller, it was imperative to address this issue for enhanced customer retention and business sustainability. This prompted a deeper investigation into the factors contributing to churn.

Additionally, I utilized a heatmap to reveal the features strongly correlated with churn. Notable factors included total day charge, customer service calls, and the ratio of total day charge to the plan. This analysis provided a foundation for making data-informed recommendations to address customer churn.

### Reccomendations

Based on the EDA findings, I proposed several recommendations for SyriaTel:

Tailored Service Plans: SyriaTel should consider crafting more personalized service plans that cater to individual customer needs. Offering more flexible and unlimited plans may reduce customer churn, particularly for customers sensitive to daily usage costs.

Cost Management: To mitigate churn, it is crucial to address the high daily usage costs that appear to be driving customers away. SyriaTel can work on optimizing pricing and service offerings.

Customer Service Training: Providing training and resources to customer service representatives is essential. Empowering employees to effectively address customer concerns can prevent escalations that lead to churn.


#### Final Model Findings

The final predictive model, a Random Forest classifier, validated the insights gained during EDA. It achieved a remarkable accuracy rate of 95% in classifying churn. Furthermore, the recall metric, which measures the model's ability to correctly identify true positive cases, stood at an impressive 82%. This emphasizes the model's effectiveness in identifying and addressing customer churn, and it aligns with the earlier heatmap analysis.

The project's outcomes can empower SyriaTel to proactively address customer churn, improve service offerings, and ultimately enhance customer satisfaction and retention.
