# NBA GOAT Debate – Data Science Analysis

This project is a deep statistical dive into the legendary careers of **LeBron James** and **Michael Jordan**, using data science to explore one of the most debated questions in sports: *Who is the GOAT?*

## Summary

Using regular season and playoff stats from [Basketball Reference](https://www.basketball-reference.com/), I applied a combination of:

- **Weighted scoring systems** for both regular season and playoffs
- **Visual comparisons** using advanced stats across careers
- **Linear regression models** to predict team wins based on player performance
- **Logistic regression models** to estimate the probability of high-win seasons
- **Permutation hypothesis testing** to assess differences in offensive metrics

The goal was not to end the debate—but to measure it with data-driven objectivity.

## Repository Contents

- `NBA_project.pdf` — Full report with code, models, graphs, and interpretations
- `NBA_project_powerpoint.pdf` — Slide deck summarizing methods, visuals, and conclusions

## Tools & Techniques
-Cleaned and wrangled data with the pandas package in Python
- **RStudio** with `ggplot2`, `dplyr`, and modeling packages
- Custom function for stat plotting over career trajectories
- Weighted scoring system based on box score and advanced stats
- Forward stepwise selection, regularization (Lasso), and cross-validation for modeling
- Permutation testing for hypothesis evaluation

## Key Takeaways

- **Jordan** scored higher in regular season weighted stats (24–22)
- **LeBron** dominated in playoff weighted stats (37–23), showing elite longevity
- Logistic models revealed that **LeBron’s PER** was more predictive of team wins than raw scoring
- Jordan’s **Defensive Rating (DRtg)** was a significant predictor for team win percentage
- Statistical tests suggest no significant difference in prime OBPM between the two


