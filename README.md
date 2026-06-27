## task-1 Understand the Business Problem

## Business Problem Statement

The company needs to decide whether the new onboarding and activation campaign should be launched to all users. This decision impacts business leadership, product teams, marketing teams, and future users. The primary objective is to improve paid user conversion while maintaining a positive user experience. Along with improving conversions, risks such as increased refund requests, higher support tickets, lower engagement, or longer conversion times must be monitored. The recommendation should be based on experiment results, statistical evidence, and guardrail metric analysis before making a final rollout decision.

## Task 2: North Star Metric

### North Star Metric

**Paid Conversion Rate**

### Why this is the North Star Metric

Paid Conversion Rate is selected as the North Star Metric because the primary objective of the new onboarding campaign is to increase the number of users who become paying customers. A higher paid conversion rate directly reflects the effectiveness of the onboarding experience and contributes to increased business revenue and long-term growth.

### Supporting Metrics

The following metrics are considered supporting metrics because they help explain user behavior throughout the onboarding journey but do not directly measure business success:

* Landing Page Visit Rate
* Trial Start Rate
* Onboarding Completion Rate
* Average Revenue per User (ARPU)
* Average Revenue per Converted User
* Average Engagement Score

These metrics help identify where users progress or drop off during the onboarding process and provide additional context for the experiment results.

### Connection to Business Growth

Paid Conversion Rate is directly linked to business growth because an increase in paying customers leads to higher subscription revenue, improved customer acquisition efficiency, and sustainable business expansion. Improving this metric helps maximize the return on investment of the onboarding campaign.

### Risk of Optimizing Only This Metric

Focusing only on Paid Conversion Rate may lead to unintended consequences. For example, conversions may increase while refund requests, support tickets, or customer dissatisfaction also increase. Therefore, guardrail metrics such as Refund Rate, Support Ticket Rate, Days to Convert, and Engagement Score must also be monitored before making a final launch decision.

## Guardrail Metrics Evaluation

### Refund Rate
The Treatment group showed a refund rate of 0.42% compared to 0.00% in the Control group. Although refunds increased slightly, the overall refund rate remains very low and does not represent a significant business risk.

### Support Ticket Rate
The Support Ticket Rate increased from 14.72% in the Control group to 24.76% in the Treatment group. This indicates that users in the Treatment group required more support, suggesting that some aspects of the new onboarding experience may need improvement before a full rollout.

### Average Engagement Score
The average engagement score increased from 57.03 to 62.93, indicating that users who experienced the new onboarding campaign were more engaged with the product.

### Average Days to Convert
The average days to convert decreased from 8.86 days to 6.40 days. This shows that users in the Treatment group converted to paid subscriptions more quickly than users in the Control group.

### Overall Assessment
The Treatment group achieved a significant improvement in paid conversion, user engagement, and conversion speed. However, the higher Support Ticket Rate suggests that the new onboarding experience may create additional customer support needs. This should be investigated before a full rollout.
