# Task 4: A/B Testing and Hypothesis Testing

## Objective
To compare the performance of an old and a new e-commerce landing page using statistical hypothesis testing.

## Dataset
Kaggle A/B Testing Dataset

- Original records: 72,248
- Cleaned records: 72,247
- Features: 12

## Steps Performed
1. Dataset loading and inspection
2. Data quality and randomization checks
3. Missing value inspection and handling
4. Conversion rate calculation
5. Hypothesis formulation
6. Two-Proportion Z-Test
7. 95% Confidence Interval calculation
8. Confidence interval visualization
9. Chi-Square Test (Device Type vs Conversion)
10. Independent T-Test (Session Duration)
11. Statistical Power Analysis
12. Randomization checks
13. Business impact analysis
14. Final conclusion and recommendation

## Key Results

| Metric | Result |
|---|---:|
| Old Page Conversion Rate | 11.91% |
| New Page Conversion Rate | 17.74% |
| Absolute Conversion Uplift | 5.83 percentage points |
| Relative Conversion Uplift | 48.95% |
| Z-Test P-Value | 4.54 × 10⁻¹⁰⁸ |
| Old Page Revenue per Visitor | 4.47 |
| New Page Revenue per Visitor | 6.75 |

## Conclusion
The new landing page achieved a significantly higher conversion rate than the old landing page. The results support recommending the new page, while continuing to monitor conversion and revenue performance.

## Tools and Libraries
- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Google Colab
