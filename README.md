# Daily Steps Data Analysis Project
Motivation

While brainstorming for a project, I decided to analyze a dataset that reflects my daily physical activity. Using data collected from my iPhone and other manually logged details, I aim to explore patterns in my activity levels, specifically step counts, rest times, active times, and goal achievement percentages. The primary motivation for this project is to better understand my physical activity habits and identify potential areas for improvement in achieving daily fitness goals.

Through this analysis, I hope to gain insights into how different variables such as daily step count, active minutes, calories burned, and rest time are interconnected and how they influence my overall physical activity and health.

---

Tools

- Google Collab:  For coding and documenting the project.
- Pandas: Used for data manipulation, cleaning, and structuring.
- Numpy: For mathematical computations.
- Matplotlib and Seaborn: For creating clear and informative visualizations.
- Scipy: Used for statistical analysis, such as correlation calculations.

---

Data Source

The dataset for this project combines automatically tracked data from my iPhone's Health app and manually recorded metrics. It contains the following information for each day:
1. Step Count: Total number of steps taken daily.
2. Distance (km): Distance covered in kilometers based on step counts.
3. Calories (kcal): Estimated calories burned from physical activity.
4. Active Time (minutes): Time spent being physically active.
5. Floors Climbed: Number of floors climbed daily.
6. Rest Time (minutes): Time spent resting or being inactive.
7. Goal Achievement (%): Percentage of daily step goal (8000 steps) achieved.
8. Exercise Type: Type of physical activity (e.g., walking, running, none).
9. Weight (kg): Daily weight fluctuations.

The data spans several months and is stored in a `.csv` file.

---

Data Processing

The dataset was processed to ensure clarity and usability for analysis. The steps included:
1. Data Cleaning:
   - Checked for missing or inconsistent data.
   - Verified data types and corrected any formatting issues.
2. Feature Engineering:
   - Created new metrics, such as correlations between step count and other variables.
   - Simplified some columns for easier analysis (e.g., normalized rest and active times).
3. Standardization:
   - Converted date fields to a consistent datetime format.
   - Ensured all numerical values were in comparable units.

For detailed steps, refer to the `data_process.ipynb` file.

---

Data Analysis

The analysis focused on understanding the relationships between various variables in the dataset. Key areas of exploration included:

1. Step Count Trends
- Identified days with the highest and lowest step counts.
- Explored how step counts varied across different days of the week and activity types.

2. Goal Achievement Analysis
- Examined the consistency of achieving the daily step goal (8000 steps).
- Analyzed the relationship between goal achievement percentages and other variables, such as calories burned and active time.

3. Correlation Analysis
- Investigated correlations between step count, active time, rest time, and weight. For example:
  - Positive correlation between step count and calories burned.
  - Negative correlation between rest time and active time.

4. Exercise Types and Activity
- Categorized daily activity based on the type of exercise (walking, running, none).
- Compared how different exercise types influenced total step count and calories burned.

---

Findings

Daily Activity Patterns
- Step counts were generally higher during weekdays compared to weekends.
- Rest times tended to increase on days with lower step counts, indicating a recovery pattern.

Goal Achievement
- The daily step goal (8000 steps) was achieved approximately 70-80% of the time.
- Higher goal achievement percentages corresponded with increased calories burned and active minutes.

Exercise and Activity
- Walking was the most common type of physical activity, contributing significantly to daily step counts.
- Running, although less frequent, resulted in higher calorie burn rates.

Correlations
- Step counts showed a strong positive correlation with active time and calories burned.
- Rest time was negatively correlated with active time, as expected.

---

Limitations

1. Data Completeness:
   - The dataset covers a limited time frame, restricting the analysis of long-term trends.
   - Some manually logged data (e.g., exercise type) might contain subjective inaccuracies.

2. Privacy Considerations:
   - Personal data, such as location or detailed timestamps, were excluded for privacy reasons.

3. Analysis Depth:
   - The project focuses on exploratory data analysis and basic statistics. More advanced techniques, such as machine learning, could provide deeper insights.

---

Future Work

1. Seasonal Trends:
   - Extend the dataset to include more months or even years to observe seasonal changes in activity patterns.
   
2. Predictive Modeling:
   - Use machine learning techniques to predict goal achievement or step counts based on historical data.

3. Interactive Dashboards:
   - Develop an interactive visualization tool for real-time exploration of activity trends.

---

This project provides a detailed analysis of my daily activity data and highlights key insights into my physical habits. The findings not only help in understanding my current lifestyle but also provide actionable feedback for improvement.
