Business Problem Statement

The business needs to decide whether the new onboarding and activation campaign should replace the existing onboarding experience, be rejected, continue testing, or be launched only for specific customer segments.

This decision impacts business management, the marketing team, product managers, and customers because it affects customer acquisition, onboarding success, revenue generation, and the overall customer experience.

The primary metric that should improve is the paid conversion rate (converted_to_paid). Secondary success metrics include higher trial starts, increased onboarding completion, greater 30-day revenue, and improved customer engagement.

While improving conversions, the business must also monitor important risks. The new campaign should not lead to higher refund requests, more customer support tickets, lower-quality revenue, or reduced customer engagement. These are treated as guardrail metrics to ensure that business growth remains sustainable.

Before making a recommendation, evidence from the A/B experiment is required. This includes comparing the control and treatment groups using statistical analysis to determine whether observed differences in conversion, revenue, engagement, refunds, and support tickets are meaningful rather than due to random variation. The final recommendation should be based on both business impact and statistical evidence.

Data Cleaning and Preparation
Before analyzing the A/B experiment, the dataset was checked to ensure data quality and reliability.

1. Missing Values
Each column was examined for missing values using Excel functions. No critical fields should contain missing data. Any missing values should be investigated before analysis.

2. Group Counts
The number of users assigned to the Control and Treatment groups was counted to verify that both groups were reasonably balanced for comparison.

3. Duplicate User IDs
User IDs were checked for duplicates using the `COUNTIF` function. Duplicate records should be removed or investigated to ensure that each user appears only once in the experiment.

4. Binary Variable Validation
Binary variables such as conversion, onboarding completion, and refund status were checked to confirm that they contain only valid values (0 or 1). Invalid values should be corrected or excluded from analysis.

5. Revenue Outliers
Revenue values were examined using the Interquartile Range (IQR) method. Records outside the acceptable range were flagged as potential outliers for further review but were not removed automatically unless justified.

6. Segment Distribution
A Pivot Table was used to compare customer segment distribution across the Control and Treatment groups. This ensured that customer segments were reasonably balanced and that differences in results would not be caused by unequal group composition.

Summary
The dataset was reviewed for missing values, duplicate users, invalid binary values, revenue outliers, and balanced segment distribution before statistical analysis. These checks improve the reliability and validity of the experiment results.
