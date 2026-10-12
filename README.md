# DISTRICT-WISE-MISSING-PERSONS-ANALYSIS-IN-INDIA-2021-ONWARDS-
MISSING PERSONS PYTHON DATA ANALYSIS

**Author:** Adeena Salam
**Project Type:** Data Analytics | Exploratory Data Analysis (EDA)
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook
**Analysis Period:** 2021–2022

---

## Project Overview

This project focuses on analyzing district-wise missing-person data using Python. The objective is to explore patterns and trends in missing-person reports across different years, states, districts, genders, and age groups.

Using data cleaning, exploratory data analysis (EDA), statistical summaries, and visualizations, the project identifies important patterns and generates insights from the available dataset.

The analysis demonstrates how Python-based data analytics can help transform raw data into meaningful information for reporting and further investigation.

## Project Objectives

* Analyze missing-person trends across 2021 and 2022.
* Identify states and districts with higher reported numbers of missing persons.
* Examine the distribution of missing persons by gender.
* Compare missing-person reports involving children and adults.
* Investigate relationships between different missing-person categories.
* Create meaningful visualizations to communicate key findings.
* Develop practical data analytics skills using Python.

## Dataset Description

The dataset contains **1,841 records and 22 original columns**, covering district-wise missing-person information for 2021 and 2022.

The dataset includes information related to geographical locations, years, gender categories, and age groups.

### Dataset Summary

| Attribute             | Description                                     |
| --------------------- | ----------------------------------------------- |
| Records               | 1,841                                           |
| Original Columns      | 22                                              |
| Analysis Period       | 2021–2022                                       |
| Geographical Coverage | States and districts represented in the dataset |
| Missing Values        | None detected during preprocessing              |
| Duplicate Records     | None detected during preprocessing              |

Additional analytical columns were created to calculate total missing persons by gender and age group.

##  Tools and Technologies

* **Python** – Data analysis and programming
* **Pandas** – Data manipulation and aggregation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Interactive analysis and documentation

##  Project Workflow

The project follows these major steps:

1. Data Loading: Import the dataset into a Jupyter Notebook.
2. Data Inspection: Examine the dataset structure, columns, data types, and dimensions.
3. Data Cleaning: Check for missing values, duplicate records, and data consistency.
4. Data Preparation: Create derived columns for total missing persons by gender and age group.
5. Exploratory Data Analysis: Generate descriptive statistics and grouped summaries.
6. Data Visualization: Create charts to explore trends, distributions, and comparisons.
7. Correlation Analysis: Examine relationships among selected numerical variables.
8. Insight Generation: Summarize the key patterns observed in the analysis.

## Visualizations

The project includes 10 visualizations designed to explore different aspects of the dataset.

No.	Visualization	Purpose
1	Year-wise Line Chart	Compare total missing-person reports across years
2	Top 10 States Bar Chart	Identify states with higher aggregate counts
3	Gender Distribution Pie Chart	Examine the distribution by gender
4	Children vs. Adults Bar Chart	Compare missing-person counts by age group
5	Histogram with KDE	Understand the distribution of total missing-person counts
6	Gender-wise Box Plot	Examine the spread and variation in gender-specific counts
7	Male vs. Female Scatter Plot	Explore the relationship between male and female counts
8	Correlation Heatmap	Visualize correlations among selected numerical variables
9	Top 10 Districts Bar Chart	Identify districts with higher aggregate counts
10	Year-wise Gender Grouped Bar Chart	Compare gender-specific counts across years

The visualizations use a consistent black-and-red color theme to maintain a uniform presentation throughout the project.

 
## Key Findings

1. Year-wise Comparison

The aggregated dataset records the following totals:

2021: 389,844
2022: 441,964

The aggregate total was higher in 2022 than in 2021. This comparison describes the dataset's reported counts and does not, by itself, establish the reasons for the difference.

2. Gender Distribution

The aggregated gender totals are:

Female: 558,450
Male: 272,952
Transgender: 406

Female missing-person counts were higher than male and transgender counts in the analyzed data.

3. Age-group Distribution

The aggregated age-group totals are:

Adults: 670,831
Children: 160,765

The dataset contains a higher aggregate count for adults than for children.

4. State-level Patterns

Maharashtra had the highest aggregate count among the states identified in the analysis. Other states with comparatively high counts included West Bengal, Madhya Pradesh, Rajasthan, and Tamil Nadu.

5. Correlation Analysis

The analysis identified strong positive correlations between total missing-person counts and some gender- and age-specific counts.

For example, the correlation between total missing persons and adult missing persons was approximately 0.991.

These correlations should be interpreted carefully because total counts are constructed from component categories. Strong correlations are therefore partly expected and do not establish causation.

## Key Takeaways

The dataset shows a higher aggregate number of missing-person reports in 2022 than in 2021.
Female missing-person counts exceed male and transgender counts in the aggregated data.
Adult missing-person counts exceed child missing-person counts.
State- and district-level aggregation helps identify geographical differences in reported counts.
Visualizations make comparisons and distributions easier to interpret.
Correlation analysis helps examine numerical relationships but must be interpreted in the context of how the variables are constructed.

## How to Run the Project
 
### Prerequisites

Install Python and Jupyter Notebook, along with the required libraries.

1. Clone the Repository
git clone <your-github-repository-url>
2. Navigate to the Project Folder
cd District-wise-Missing-Person-Analysis
3. Install the Required Libraries
pip install pandas numpy matplotlib seaborn jupyter
4. Open Jupyter Notebook
jupyter notebook
5. Run the Notebook

Open the project notebook and execute the cells in sequence. Update the dataset path in the notebook if your dataset is stored in a different folder.

## Limitations
 
* The analysis covers only the years 2021 and 2022.
* The findings depend on the completeness, accuracy, and definitions used in the source dataset.
* Aggregated counts do not explain the reasons behind differences between states, districts, genders, or age groups.
* Correlation does not imply causation.
* The analysis does not independently verify individual missing-person cases or their outcomes.

## Future Scope

The project could be extended by:

* Incorporating data from additional years to examine longer-term trends.
* Developing interactive dashboards using Plotly or Power BI.
* Exploring geographical patterns through maps.
* Investigating additional variables, where reliable data is available.
* Building automated reports to simplify recurring analysis.
* Combining the analysis with verified contextual information to support more detailed research.

## Project Documentation

Detailed project documentation can be included in the repository as a PDF file. It describes the project overview, dataset, tools, workflow, visualizations, findings, limitations, and future scope.

## Author

Adeena Salam

Aspiring Data Analyst | Python | Pandas | NumPy | Matplotlib | Seaborn | Exploratory Data Analysis

This project demonstrates practical skills in data cleaning, exploratory data analysis, statistical interpretation, and data visualization.

## Acknowledgement

I would like to express my gratitude to everyone who supported my learning journey in data analytics. This project provided an opportunity to apply Python-based analytical techniques to a real-world data analysis problem.

Thank you for exploring my project!
