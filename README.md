# Pakistan Healthcare Analysis: Multilevel Poisson Model

This project explores the distribution of doctors across Pakistan’s districts using multilevel Poisson regression models, incorporating poverty and population data.

---

## Overview

- **Modeling doctor counts** by district and province to understand healthcare resource distribution.
- **Poisson regression:** A common approach for modeling count data, assuming the mean and variance are equal.
- **Overdispersion:** When the observed variance exceeds the mean, indicating the Poisson assumption may not hold.
- **Negative binomial regression:** An extension of Poisson regression that accounts for overdispersion by adding a dispersion parameter.
- **Offsets:** Used to adjust for differing population sizes in each district, modeling the rate of doctors per person rather than raw counts.
- **Multilevel models:** Also called hierarchical models, these allow for variation at multiple levels (here, districts nested within provinces), capturing province-specific effects on doctor counts.
- **Visualizations:** Geographic maps and plots to highlight disparities in doctor availability across provinces and poverty levels.

---

## How to Run

1. Clone this repo.
2. Load data and shapefiles (ensure shapefiles are placed in the `data/` folder).
3. Run the R Markdown file `Quiz4_analysis.Rmd` to reproduce the full analysis and generate figures.

---

## References

- Data: [Kaggle - Pakistan District Profile](https://www.kaggle.com/datasets/alikhan83/pakistan-district-profile)  
- Source Data: [Open Data Pakistan](https://opendata.com.pk/dataset/district-profiles-all-districts-of-pakistan)

---

## License

MIT License

---

*Made with care by Sonya Eason*
