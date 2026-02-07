# A/B Testing – Hypothesis Testing in Python

## Objective
To evaluate whether a new treatment (variation) improves conversion rate compared to the control group using A/B testing.

## Dataset
Marketing A/B Testing Dataset  
Columns:
- user_id: Unique user identifier
- variation: control or treatment group
- converted: 1 if user converted, 0 otherwise

## Tools & Libraries
- Google Colab
- Python
- pandas
- numpy
- scipy
- matplotlib

## Methodology
1. Loaded and explored the dataset.
2. Segmented users into control and treatment groups.
3. Defined null and alternative hypotheses.
4. Calculated conversion rates for both groups.
5. Applied Chi-Square test (binary conversion metric).
6. Evaluated statistical significance using p-value.
7. Computed 95% confidence interval for conversion difference.
8. Visualized conversion rates.
9. Provided a business recommendation.

## Results
- Treatment group showed a higher conversion rate than control.
- The p-value was below 0.05, indicating statistical significance.
- Confidence interval supported the observed improvement.

## Business Recommendation
Roll out the treatment version to all users to improve conversions.