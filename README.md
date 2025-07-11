# Salary & Population Data Analysis

This project is an exploratory and statistical analysis of salary data for data professionals across different countries, combined with global population and demographic data.

###  Objectives
- Understand salary distribution by **experience level**, **remote status**, **company size**, and **continent**
- Investigate correlation between **population growth rate** and **average salary**
- Perform **statistical testing** (ANOVA & Pearson correlation) to detect significant patterns


### Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scipy, Statsmodels)
- Jupyter Notebook
- GitHub


###  Key Insights
- Significant salary differences were found across continents using ANOVA (p < 0.05)
- Salary is moderately correlated with population growth rate in some countries
- Remote work patterns vary widely based on company size and region

###  Files
- `data me.ipynb`: Full notebook with cleaning, analysis, visualizations, and statistical tests
- `ds_salaries_prep.csv`: Salary dataset
- `countries-table_prep.csv`: Country demographic dataset
- `salaries_cleaned.csv` and `population_cleaned.csv`: Cleaned outputs after preprocessing

### Statistical Methods
- **One-way ANOVA**: Salary differences by continent
- **Tukey HSD**: Post-hoc comparison of group means
- **Pearson Correlation**: Relationship between population growth and salary


###  Sample Visualizations

- **Average Salary Over Years**  
  ![Average Salary Over Years](images/average_salary_over_years.png)

- **Average Salary by Continent and Company Size**  
  ![Average Salary by Continent and Company Size](images/salary_by_continent_company_size.png)

- **Average Salary by Experience Level and Remote Work Status**  
  ![Average Salary by Experience Level and Remote Work Status](images/salary_by_experience_remote.png)

- **Average Salary vs Population Growth Rate**  
  ![Average Salary vs Population Growth Rate](images/salary_vs_population_growth.png)


### Author
**Roya Mohammadi**  
https://www.linkedin.com/in/roya-mohammadi95/
Email: royamohamadi195@gmail.com


If you find this project useful, feel free to star the repo or share feedback!
