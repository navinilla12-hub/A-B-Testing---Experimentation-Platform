Title: A/B Testing & Experimentation Analytics Platform

Problem Statement:

Companies frequently run experiments to improve product features or marketing strategies. However, determining whether a change is statistically significant requires proper hypothesis testing.

This project builds a framework to:
Analyze A/B test results
Determine statistical significance
Measure performance lift

Objectives:
Compare control vs treatment groups
Perform hypothesis testing
Calculate p-values and statistical significance
Provide business recommendations

Dataset:
Contains:
User group (control/treatment)
Landing page
Conversion outcome

Methodology:
1. Data Cleaning
Removed inconsistent rows
Ensured proper group assignments
2. Conversion Analysis
Calculated conversion rates for both groups
3. Statistical Testing
Performed independent t-test
Evaluated significance using p-value
4. Business Metrics
Calculated conversion lift
Interpreted results for decision-making

Results:
Determined whether new feature improves conversions
Quantified performance improvement

Business Impact:
Enables data-driven product decisions
Reduces risk of incorrect feature rollouts
Improves marketing effectiveness

Tech Stack:
Python
Pandas
SciPy

Future Improvements:
Bayesian A/B testing
Sequential testing
