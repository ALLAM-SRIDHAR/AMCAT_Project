# Job Data Analysis with AMCAT Dataset (EDA project on Engineering Graduates Employment Outcomes!) 

## Overview
This repository contains a Jupyter notebook that performs data analysis on a dataset related to job roles and salaries, using the AMCAT dataset. The project involves data preprocessing, visualization, and basic statistical analysis to extract meaningful insights about various job-related factors.

## Dataset
The dataset (`AMCAT_data.csv`) includes the following fields:
- **ID**: Unique identifier for each record
- **Salary**: Salary of the individual
- **DOJ**: Date of Joining
- **DOL**: Date of Leaving
- **Designation**: Job role or title
- **JobCity**: Location of the job
- **Education Data**: Includes fields such as 10th/12th percentages, board, graduation year, degree, etc.
- **Skills**: Scores in English, Logical reasoning, Quantitative ability, Domain knowledge, Computer programming, etc.

## Key Operations
1. **Data Loading and Cleaning**: Load the dataset and remove unnecessary columns.
2. **Exploratory Data Analysis (EDA)**: Perform basic statistical analysis and data visualization using libraries like Seaborn and Matplotlib.
3. **Feature Engineering**: Transform and clean data fields, such as removing unnecessary columns and handling missing values.
4. **Statistical Analysis**: Measure attributes such as skewness and kurtosis to understand data distribution.

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

2. Ensure you have the necessary Python libraries installed:
   pip install pandas numpy matplotlib seaborn scipy
3. Run the Jupyter notebook to explore the data and perform the analysis.

## Jupyter Notebook Link
http://localhost:8890/notebooks/innomatics/AMCAT.ipynb
