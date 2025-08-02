# PK Health Analysis: Modeling Doctors and Poverty in Pakistan

This project investigates how poverty relates to the distribution of doctors across districts in Pakistan, using Poisson and multilevel regression models to account for geographic variation.

---

## Project Overview

Using data from the Sustainable Development Policy Institute (SDPI), this analysis models healthcare access through the lens of doctor availability and socio-economic conditions. We focus on:

- Understanding the impact of poverty on healthcare workforce distribution  
- Visualizing geographic disparities across provinces and districts  
- Applying appropriate count data models to reveal meaningful insights  

Our goal is to blend rigorous statistical modeling with spatial understanding to inform public health discussions in Pakistan.

---

## Tools & Technologies

- **R** with `tidyverse` for data manipulation and visualization  
- `sf` for handling geographic shapefiles and maps  
- `glmmTMB` and `MASS` for Poisson and negative binomial regression modeling  
- `ggplot2` and `ggrepel` for clean and informative plots  

---

## Data Sources

- [Pakistan District Profiles](https://opendata.com.pk/dataset/district-profiles-all-districts-of-pakistan) (SDPI)  
- [Kaggle Dataset](https://www.kaggle.com/datasets/alikhan83/pakistan-district-profile) (aggregated data)  

---

## Getting Started

1. Clone this repository  
2. Ensure the `data/` folder contains all necessary CSV and shapefile components  
3. Run the provided R Markdown analysis file to reproduce all results and visualizations  

---

## Visual Highlights

### Map of Pakistan Provinces  
![Map of Pakistan Provinces](images/pakistan_provinces_map.png)  
*Spatial visualization of the 7 provinces and their districts.*

---

### Number of Doctors by Province  
![Doctors by Province Bar Plot](images/doctors_by_province.png)  
*Bar plot showing the distribution of doctors across provinces.*

---

### Multilevel Model Overview  
![Multilevel Model Diagram](images/multilevel_model_diagram.png)  
*Conceptual diagram illustrating the multilevel modeling approach accounting for district and province variation.*

---

## Unique Aspect

This project combines multilevel modeling with geographic visualization to capture both numerical and spatial dimensions of healthcare inequality — revealing patterns that might otherwise remain hidden in aggregated data.

---

## Acknowledgments

Thanks to SDPI and the open data community for making this rich dataset publicly accessible, enabling meaningful research.

---

## About

Analysis was refined with the help of AI-assisted tools to enhance clarity and visualization, aiming to provide a seamless and insightful research experience.

---

⭐ If you find this project helpful, please consider starring the repository!

---

Happy analyzing.  
