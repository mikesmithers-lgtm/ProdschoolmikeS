# The Signals · FinWise

> Module 4 · Data & Analytics. The data pattern you found and the indicators you'll steer by.

## The data pattern

The headline is that my thoughts around indicators needed revision.  Import rate against conversion has a weak correlation of 0.05 and therefore there is no relationship.  Modelling usage against conversion is at 0.26 so stronger but still weaker than required.  

The hypothesis chain isn’t supported yet. Neither Import Rate nor Modeling Usage shows a usable link to conversion in this data. That doesn’t prove the North Star is wrong, but it means the leading indicators need better evidence before they are committed to.

We need to keep the leading indicators but possibly add Financial modelling feature usage and churn as this does have a correlation.

_Metric patterns: Conversion, Ceiling because the metric is stable. Modeling usage, Cliff - steep drop off of feature usage. Import usage, Ceiling - plateauing at a similar percentage. Session duration, Cliff sharp fall but does have a partial rebound. Sessions/user, Cliff and ceiling.._

_Correlation test: Revised._

_____

## Leading indicators

- **% of users who import financial data in their first session:** Importing is the gate to modeling, so users who never import can’t reach the North Star.
- **Median time from first import to first modeling output:** Long gaps signal friction in the handoff, and it’s a quick, concrete thing to experiment on first, such as with guided setup or templates.

_____

## Lagging indicators

- **Trialled to paid conversion rate among users who reached first modeeling putput:** If users who hit the North Star convert at a higher rate, the strategy is working at scale.

_____
