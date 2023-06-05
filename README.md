# Decision_making_in_business
**Project Description**

Client - a large online store.

Goal - to analyze the list of hypotheses prepared by me and the marketing department, and select those that will increase the revenue of the online store.

Tasks:
- prioritize hypotheses
- launch A/B test
- analyze the results
- Data Description

**Part 1 (Hypotheses)**

- Hypothesis - a brief description of the hypothesis;
- Reach - user coverage on a 10-point scale;
- Impact - impact on users on a 10-point scale;
- Confidence - confidence in the hypothesis on a 10-point scale;
- Efforts - resource costs for testing the hypothesis on a 10-point scale. The higher the Efforts value, the more expensive the hypothesis testing.

**Part 2**

Dataset with orders:
- transactionId - order ID;
- visitorId - ID of the user who made the order;
- date - date when the order was placed;
- revenue - revenue of the order;
- group - A/B test group to which the order belongs.

Dataset with visitors:
- date - date;
- group - A/B test group;
- visitors - number of users on the specified date in the specified A/B test group.

**Conclusion on the test results**

After analyzing the A/B test, we can draw several conclusions:
- There is a statistically significant difference in the average number of orders between groups based on "raw" and "clean" data. The p-value is less than 0.05.
- There is no statistically significant difference in the average order value between groups based on "raw" and "clean" data. The p-value is practically the same and greater than 0.05.
- The relative gain in the average number of orders of group "B" over "A" is 17.4% (compared to 13.9% based on "raw" data).
- The average order value of group B is equal to the average order value of group A.
- The chart of the difference in the average number of orders between groups shows that the results of group B are better than those of group A.
- The chart of the difference in the average order value shows that the results of group A are not significantly different from those of group B.
