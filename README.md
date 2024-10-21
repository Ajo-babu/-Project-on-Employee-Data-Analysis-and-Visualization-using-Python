# -Project-on-Employee-Data-Analysis-and-Visualization-using-Python
This is a Python project Analysis of Employee Data: Exploring Team Distribution, Positions, Age Groups, Salary Expenditures, and Correlations

Project Report
Project Title: Employee Data Analysis and Visualization
Introduction
This project focuses on analyzing a given dataset that contains various attributes of employees, such as their names, teams, positions, ages, heights, weights, colleges, and salaries. The dataset required several preprocessing steps and analytical tasks to gain insights into the distribution of employees across teams and positions, determine salary expenditure, and investigate correlations between employee attributes.

The following report outlines the key steps undertaken, the findings derived from the analysis, and the visualizations used to present the results effectively. Python was used for all computations, data cleaning, and visualizations, utilizing libraries such as NumPy, Pandas, Matplotlib, and Seaborn.

Preprocessing:
Objective: Correct the data and ensure its consistency and integrity.
Task: The "Height" column had some incorrect or missing values. To resolve this:
Replaced the values in the "Height" column with random numbers between 150 and 180 to ensure consistency.
Addressed missing values in the "College" and "Salary" columns by replacing them with the mode values.
This step ensured that the dataset was clean and ready for analysis.

Analysis Tasks:
1. Distribution of Employees Across Teams:
Objective: Calculate the distribution of employees across each team and their percentage split relative to the total number of employees.
Findings:
The team New Orleans Pelicans had the highest percentage of employees (4.14%), followed by Memphis Grizzlies (3.9%) and Utah Jazz (3.4%).
A data frame was created to show the number of employees and the percentage distribution for each team.
Visualizations:
Bar Chart: Showed the number of employees per team.
Pie Chart: Represented the percentage of employees per team for clearer comparative understanding.

2. Segregation of Employees by Position:
Objective: Segregate employees based on their positions within the company.
Findings:
The SG (Shooting Guard) position had the highest number of employees (102 employees), followed by PF (Power Forward) with 100 employees and PG (Point Guard) with 92 employees.
Visualizations:
Bar Chart: Displayed the number of employees across different positions.
Pie Chart: Presented the percentage distribution of employees by position for a clear visual comparison

3. Identification of the Predominant Age Group:
Objective: Identify the predominant age group among the employees.
Findings:
The age range of 20-30 years was the predominant group, comprising 72.9% of the employees, followed by the 31-40 age group.
The age distribution showed a clear concentration of younger employees.
Visualizations:
Donut Chart: Displayed the proportion of employees in each age group.
Histogram: Showed the distribution of ages within the dataset.
Box Plot: Highlighted the spread of ages and identified outliers, with the maximum age being 90 years and the minimum age being 20

4. Highest Salary Expenditure by Team and Position:
Objective: Discover which team and position combination had the highest salary expenditure.
Findings:
The SF (Small Forward) position for Los Angeles Lakers had the highest salary expenditure, followed by the PF (Power Forward) position for Miami Heat.
Visualizations:
Dist Plot: Showed the overall distribution of salaries among employees.
Line Plot: Represented the salary expenditure for different teams and positions, allowing for easy comparison of salary outflows.

5. Correlation Between Age and Salary:
Objective: Investigate if there is any correlation between an employee's age and their salary.
Findings:
The correlation analysis showed a positive relationship between age and salary, suggesting that as employees' age increases, their salary tends to increase as well.
Visualizations:
Joint Plot: Displayed a scatter plot along with the marginal distributions of both age and salary.
Scatter Plot: Directly visualized the relationship between age and salary.
Regression Plot: Showed a trend line that further confirmed the positive correlation between age and salary.

Visualizations Used:
The project made use of multiple visualizations to represent the data effectively and provide clear insights. Below are the visualizations used in different parts of the analysis:

Bar Chart: Used to show the distribution of employees across teams and positions.
Pie Chart: Visualized the percentage split of employees by teams and positions.
Donut Chart: Represented the proportion of employees in different age groups.
Histogram: Showed the overall age distribution of employees.
Box Plot: Highlighted the spread and outliers in the age data.
Dist Plot: Visualized the distribution of salaries among employees.
Line Plot: Represented salary expenditure for different teams and positions.
Joint Scatter Plot: Combined scatter plot with marginal distributions to show correlation between age and salary.
Scatter Plot: Visualized the direct relationship between age and salary.
Regression Plot: Showed the trend line to confirm the positive correlation between age and salary.


Conclusion
Through a structured approach to data preprocessing, analysis, and visualization, the project successfully addressed the key objectives. Insights were gained into employee distribution by team and position, predominant age groups, salary expenditure, and the correlation between age and salary.

The visualizations, which included bar charts, pie charts, histograms, box plots, and regression plots, provided a comprehensive understanding of the dataset and its underlying patterns.

This project was completed using Python with the support of the following libraries:

NumPy for numerical operations,
Pandas for data manipulation and analysis,
Matplotlib for plotting and visualization, and
Seaborn for enhanced data visualization with advanced plots.

Overall, the project demonstrates the power of data analysis and visualization in gaining actionable insights from datasets, which can be beneficial in decision-making processes within organizations
