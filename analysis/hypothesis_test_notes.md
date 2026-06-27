# Hypothesis Test Notes

## Metric Being Tested

Paid Conversion Rate

## Null Hypothesis (H₀)

There is no significant difference in the Paid Conversion Rate between the Control group and the Treatment group.

## Alternative Hypothesis (H₁)

The Treatment group has a significantly higher Paid Conversion Rate than the Control group.

## Type of Test

One-tailed hypothesis test.

## Significance Level

α = 0.05 (5%)

## Reason for Choosing this Metric

Paid Conversion Rate is the North Star Metric for this experiment because the primary objective of the new onboarding campaign is to increase the number of users who become paying customers. This metric directly reflects the success of the campaign and its impact on business growth.

## Decision Rule

* If the p-value is less than 0.05, reject the Null Hypothesis.
* If the p-value is greater than or equal to 0.05, fail to reject the Null Hypothesis.

## Interpretation Logic

If the Treatment group shows a statistically significant improvement in Paid Conversion Rate without negatively affecting the guardrail metrics, the new onboarding campaign can be recommended for rollout. Otherwise, additional testing or improvements should be considered before a full launch.


## Test Results

- Mean Paid Conversion Rate (Control): 3.17%
- Mean Paid Conversion Rate (Treatment): 6.99%
- One-tailed p-value: 0.00053
- Significance Level (α): 0.05

## Conclusion

Since the p-value (0.00053) is less than the significance level of 0.05, the Null Hypothesis is rejected. The Treatment group achieved a statistically significant improvement in Paid Conversion Rate compared to the Control group.

## Business Interpretation

The new onboarding campaign significantly improves paid user conversion. However, before recommending a full rollout, guardrail metrics such as Refund Rate, Support Ticket Rate, Engagement Score, and Days to Convert should also be evaluated to ensure the improvement does not negatively impact user experience or business performance.