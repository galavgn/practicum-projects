### Data

The dataset 'Hypo' contains the following fields:

- Hypotheses — brief descriptions of the hypotheses
- Reach — user reach, on a scale of one to ten
- Impact — impact on users, on a scale of one to ten
- Confidence — confidence in the hypothesis, on a scale of one to ten
- Effort — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

The dataset 'Orders' contains the following fields:

- transactionId — order identifier
- visitorId — identifier of the user who placed the order
- date — of the order
- revenue — from the order
- group — the A/B test group that the user belongs to

The dataset 'Visits' contains the following fields:

- date — date
- group — A/B test group
- visits — the number of visits on the date specified in the A/B test group specified

### Goal
- To prioritize these hypotheses
- Launch an A/B test and analyze the results.

### Libraries
pandas, numpy, matpltotlib, seaborn, plotly, skipy, datetime
