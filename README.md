# IntroDS
2024fall

# IntroDS_final

## 📌 Project Overview
This repository contains the final project for the Introduction to Data Science course. The project analyzes the National Crime Victimization Survey (NCVS), a annual data collected by the U.S. Census Bureau since 1972. It collects information on nonfatal personal crimes, personal and household property crimesto investigate the consequneces of crimes, estimate the numbers and types of crimes that are not reported to the police.

The report addresses the following points:

A.  **Introduce the dataset**.  Describe the data. Where does it come from? Why was it collected (what are the researchers interested in studying)? Was it an experiment or an observational study? Describe the sampling process. How many variables are there? List a few. How many observations (i.e., rows)? How many distinct households? Using what you have learned about data collection, is this a biased or unbiased sample? Why?

B.  **Characteristics of sample**. Describe the sample of people and households in the dataset.  Summarize the distributions of 3 or more of the characteristics (variables) of the people and households.  Some interesting variables you may consider include: marital status, employment, age, income etc. Choose at least 1 categorical and 1 numerical variable. You could include a graph or table for each distribution. 

C. **Relationships between variables.**  Now, shift focus from distributions of single variables to relationships between variables. You should investigate at least 2 of the individual or household characteristics (race, sex, education...) and at least two of the crime related variables.  For example, do you find evidence that those with levels of education are victims of less crime?  Describe any associations you find and the methods you use to investigate their significance. 

D. **Provide context**  To the best of your knowledge, what do the relationships you discovered imply? Do you think the associations are causal? What are some potential confounders that may explain the relationships?  What are some questions that you would like to answer but are unable to with the current data set alone?  What data would you need to be able to answer them?

E. **Conclusion/Self-Assessment** What did you learn from analyzing this dataset?

## 📁 Repository Structure
```
├── (data)             # Raw and processed datasets
├── *.ipynb        # Jupyter Notebooks with exploratory data analysis and modeling 
├── report.pdf          # Project reports and documentation
├── README.md         # Project overview and instructions
```

## 📊 Dataset
- **Source**: [National Crime Victimization Survey (NCVS)](https://www.icpsr.umich.edu/web/NACJD/studies/38090/summary), [U.S. Census Bureau’s data (from statista)](https://www.statista.com/statistics/758502/percentage-distribution-of-household-income-in-the-us/), [U.S. Census Bureau’s data](https://www.census.gov/data/tables/2023/dec/2020-census-demographic-profile.html)

## 🚀 Installation & Setup
To run the project, follow these steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/Gentlemath/IntroDS_final.git
   cd IntroDS_final
   ```
2. Create and activate a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

## 🏗️ Usage
- Run the Jupyter Notebooks inside `notebooks/` to explore the data and train models.
- Execute Python scripts in `src/` for automated processing.
- Use `reports/` to view findings and results.

## 📜 License
This project is licensed under the [MIT License](LICENSE).

## 📞 Contact
For any questions or collaborations, feel free to reach out to [Gentlemath](https://github.com/Gentlemath).


