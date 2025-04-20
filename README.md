# python module end project
 
ABC Company Employee Data Analysis

This project is a comprehensive employee data analysis for ABC Company, completed as the final assignment for the Python module. The dataset includes detailed records of 458 employees across various basketball teams. The primary objective is to clean and preprocess the data, analyze team and employee demographics, evaluate salary distribution, and uncover relationships between age and salary through visual storytelling.


Preprocessing Steps
	•	Height Correction: The Height column originally contained invalid datetime values. These were replaced with randomly generated realistic height values between 150 cm and 180 cm.
	•	Missing Values: The College column had missing entries, which were filled with "Unknown" to maintain consistency.
	•	Data Cleaning: Salary-related tasks excluded rows with null salary values to ensure accuracy in calculations and visualizations.


Analysis Tasks

1. Team Distribution
	•	Counted employees in each team.
	•	Calculated the percentage of employees relative to the total.
	•	Visualization: Bar chart with custom color palette.

2. Position Segregation
	•	Identified and grouped employees based on their positions (e.g., PG, SG, SF).
	•	Visualization: Bar chart displaying the number of position.

3. Age Group Analysis
	•	Segregated employees into age bins (20–25, 26–30, etc.).
	•	Identified the most common age group.
	•	Visualization: Bar chart showing age group distribution.

4. Salary Expenditure
	•	Calculated total salary expenditure by team and position.
	•	Found which team and position account for the highest overall salary spending.
	•	Visualization: Bar chart for teams, pie chart for top 5 positions by salary.

5. Age vs. Salary Correlation
	•	Investigated the relationship between employee age and salary.
	•	Found a weak positive correlation.
	•	Visualization: Scatter plot with regression line to highlight the trend.


Graphical Representations

Each task was paired with an appropriate visual to support the insight:
	•	Bar Charts: For team distribution, age groups, and salary by team.
	•	Pie Charts: For top 5 positions by salary.
	•	Scatter Plot: To show correlation between age and salary.

Visuals were designed using matplotlib and seaborn to ensure clarity, accuracy, and aesthetics.

Key Insights
	•	The New Orleans Pelicans have the highest number of employees.
	•	The most common positions are Shooting Guard (SG) and Power Forward (PF).
	•	The majority of employees fall within the 26–30 age range, indicating a young workforce.
	•	The Cleveland Cavaliers have the highest total salary expenditure among teams.
	•	Position-wise, a role other than Point Guard (PG)—such as Center or Small Forward—accounted for the highest salary.
	•	There is a weak positive correlation between age and salary, suggesting that more experienced employees tend to earn slightly more.

Conclusion

This project demonstrates end-to-end data analysis using Python, covering data preprocessing, statistical summaries, visualizations, and storytelling. It highlights the ability to transform raw data into actionable insights, making it valuable for both academic and real-world data science applications.
