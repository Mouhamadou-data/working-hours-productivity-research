# Working Hours and Economic Productivity: A Cross-Country Analysis

## Overview

This project investigates whether reducing average working hours improves or harms economic productivity across countries. Using data from Our World in Data, I analyzed the relationship between annual working hours and GDP per hour worked (labor productivity) for multiple countries over time.

## Research Question

**Does reducing average working hours improve or harm economic productivity across countries?**

## Key Findings

- **More hours ≠ more output**: Countries with lower average working hours tend to have higher productivity (GDP per hour worked)
- **A 1% increase in working hours is associated with a 0.67% decrease in productivity** (log-log regression, R² = 0.94)
- **Income level matters**: High-income countries show stronger productivity gains from reduced hours
- **Global trend**: Over time, working hours have decreased while productivity has increased

These findings support ongoing debates about work-life balance and the 4-day work week.

## Methods

- Correlation analysis between working hours and productivity
- Comparison across income groups (high, upper-middle, lower-middle, low income)
- Three regression models: Simple OLS, Multiple OLS (controlling for GDP), and Log-Log (elasticity)
- Longitudinal trend analysis

## Tools & Libraries

- Python (pandas, numpy)
- Visualization (matplotlib, seaborn)
- Statistical analysis (scipy, statsmodels)

## Data Sources

- [Our World in Data - Working Hours](https://ourworldindata.org/working-hours)
- [Our World in Data - Economic Growth](https://ourworldindata.org/economic-growth)
- Penn World Table 9.1
- World Bank Income Classifications

## Files

- `Working_Hours___Productivity.ipynb` — Full analysis notebook with code, visualizations, and findings
- `working_hours_productivity.pptx` — Presentation summarizing key insights

## Author

**Mouhamadou SENE**  
MSc Data Science & Organizational Behavior  
December 2025
