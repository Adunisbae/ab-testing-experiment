# A/B Testing Experiment: User Engagement Uplift

## Objective
Evaluate whether a new product experience (treatment) increases user engagement compared to the existing experience (control).

## Experiment Design
- Randomized A/B test with 50/50 split
- ~20,000 simulated users
- Primary metric: Conversion rate
- Secondary metrics: Time to convert, 7-day retention

## Key Results
- Treatment conversion rate exceeded control by ~2.4%
- Bootstrap 95% confidence interval excluded zero
- Results indicate statistically significant uplift

## Visual Evidence
The figures below were generated from the experiment:
- Conversion rate comparison with confidence intervals
- Bootstrap distribution of conversion rate difference
- Time-to-conversion comparison

(See `figures/` folder.)

## Recommendation
Proceed with a staged rollout of the treatment while monitoring long-term retention and downstream engagement metrics.

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter
