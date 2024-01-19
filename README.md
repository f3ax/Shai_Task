Summary:

Data Exploration and Cleaning:
The dataset includes information on employee salaries, job titles, year of employment, and other factors effecting the total pay. Basic data exploration revealed that the dataset contains 148654 records of employees with 13 columns, further statistical description revealed a wide range of salaries, with a mean (Average) of 74,768 and a maximum of over 567,000.

Basic visualization revealed a wide range of job titles that were not suitable for graphs, titles will have to be grouped into departments for more accurate visualization of employee distribution across departments.

Data cleaning involved handling missing values in several columns, ensuring accurate analysis, missing values in employee salary columns were filled with 0's, as there are several columns effecting the total pay (see relevant code block), also missing values in string columns were filled with NaN.

Analysis and Findings:
Grouped analysis: Comparing average salaries across Job Titles and Years revealed variations in compensation.

For example, some higher-paying positions like Zoo Curator, Acupuncturist, and X-Ray Laboratory Aide appeared to have the highest salaries, while Accountant Interns had a lower average salary. Salary trends across Years showed a slight increase over time, with 2013 having the highest average salary. Correlation analysis: A strong positive correlation (0.95) was identified between Base Pay and Total Pay, indicating that Base Pay significantly contributes to overall employee compensation, even though previous data exploration showed some missing values in the base pay column, which means that for some employees the base pay was not the main contributor to their total pay.

Key Insights and Takeaways:
This analysis provides valuable insights into the salary distribution and variations within the provided dataset. Targeting job titles with higher average salaries could be a potential strategy for increasing income within that organization. The strong correlation between Base Pay and Total Pay suggests that focusing on base salary negotiations might be crucial for maximizing overall compensation.

Additional Potential:
Further analysis could involve exploring the impact of other factors like experience level, education, and department on salary. Visualizations like boxplots or heatmaps could be used to create a more detailed picture of salary distribution across different groups.
