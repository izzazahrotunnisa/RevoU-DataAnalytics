# RevoU-DataAnalytics
Certified 1 Week Course on Data Analytics 

# Academic Performance Insights: Student Exam Analysis
This project is part of a five-day short course designed to introduce learners to the field of data analysis. The course provides an overview of the data analyst career path, along with hands-on practice in performing core responsibilities such as data cleaning, exploration, visualization, and insight generation.

For this project, publicly available data was provided to allow learners to practice key data analysis techniques using tools like Google Sheets and Google Slides. The project emphasizes both the analytical process and the presentation of findings, ensuring that insights are communicated effectively to stakeholders.

The goal is to develop a functional dashboard, explore trends in the dataset, and generate actionable insights while applying standard data cleaning and preparation techniques.

---

## Problem Statement 
Organizations often collect large amounts of data, but without proper analysis, it is difficult to extract meaningful insights. This project focuses on exploring a dataset to identify key trends, patterns, and points of interest that could support decision-making.

The specific challenges addressed in this project include:

1. Data Preparation: Cleaning the dataset by removing duplicates, handling missing values, and filtering relevant records to ensure accurate analysis.
2. Data Exploration: Identifying trends and patterns in the data that are meaningful for stakeholders.
3. Visualization and Communication: Creating visualizations and dashboards using Google Sheets or Looker Studio to clearly communicate findings.

Ultimately, this project aims to provide a practical demonstration of how data analysis techniques can be applied to extract insights, support data-driven decisions, and communicate results effectively.

---

## Dataset Information
The dataset used in this project is sourced from a publicly available dataset on Kaggle: **“Students Performance in Exams”** (link: https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data). 
This dataset contains demographic and academic performance information for students, allowing for analysis of score distributions and influencing factors across different groups.

### Original Variables

The dataset includes the following core variables:

- Gender – Student gender (male or female).
- Race/ethnicity – Student ethnic group identifiers (e.g., Group A, Group B, Group C, Group D, Group E).
- Parental level of education – Highest level of education attained by a student’s parent(s) (e.g., some college, associate’s degree, high school, some high school, bachelor’s degree).
- Lunch – Type of lunch provided (standard or free/reduced).
- Test preparation course – Status of test preparation (none or completed).
- Math score – Student’s score in the mathematics exam.
- Reading score – Student’s score in the reading exam.
- Writing score – Student’s score in the writing exam.

These variables provide both demographic and performance-based information, enabling comprehensive analysis of how different factors relate to student outcomes.

### Additional Variables Created

To support more detailed analysis and visualization, the following new variables were derived and added during data preparation:

- Student ID – A unique identifier assigned to each student for tracking and visualization purposes.
- Average reading score – The student’s reading score normalized or presented for comparative analysis.
- Average math score – The student’s math score restructured for analytical clarity.
- Average writing score – The student’s writing score reformatted to support comparative insights.
- Total score – Sum of math, reading, and writing scores for an overall performance measure.
- Average score overall – The average of all three subject scores (math, reading, writing), providing a single metric to evaluate overall academic performance.

These additional variables enhance the dataset’s utility for ranking, comparative analysis, trend identification, and dashboard visualization.

---

## Tools Used
For this project, Google Sheets was used as the primary tool for both data preparation and visualization. 
It facilitated exporting and cleaning the dataset, performing transformations such as calculating total scores and averages, and creating new variables.
Additionally, Google Sheets was used to generate charts and visualizations, enabling the exploration of trends and insights in a clear and interactive manner.

---

## Methodology 
This project followed a structured approach to explore, analyze, and visualize student performance data. The methodology can be summarized in the following steps:

1. Data Acquisition
    - The original dataset was obtained from Kaggle ([Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams/data)).
    - The dataset includes demographic information and exam scores for students.
2. Data Cleaning and Preparation
    - Imported the dataset into Google Sheets.
    - Checked for missing values, duplicates, and inconsistencies, and cleaned the data accordingly.
    - Added new variables to enhance analysis:
        - Student ID – unique identifier for each student
        - Average math score, average reading score, average writing score – to support per-subject analysis
          Total score – sum of all three subject scores
          Average score overall – mean of all three subject scores
3. Data Transformation and Exploration
    - Calculated aggregate measures such as average scores by gender, parental education level, lunch type, test preparation course, and ethnicity.
    - Applied filter functions and sorting to identify top-performing students and their respective statistics and analyze trends across different groups.
4. Data Visualization
    - Used Google Sheets to create charts including:
        - Bar charts for comparing scores across subjects and demographic groups
        - Pie charts to visualize the proportion of students meeting certain performance thresholds
        - Scatter plots and rankings to highlight top performers and relationships between variables
    - Designed dashboards to combine multiple visualizations for easy interpretation of trends and insights.
5. Insight Generation
    - Analyzed the visualizations to identify patterns and trends in student performance.
    - Summarized findings for presentation to stakeholders, highlighting key factors that may influence academic outcomes.

This methodology ensures that the data is properly cleaned, structured, and visualized to support meaningful insights and effective communication of results.

---

## Features of Dashboard
The dashboard created for this project provides a comprehensive overview of student performance through a range of visualizations, KPI indicators, and supporting tables. Each feature is designed to highlight key insights, support comparison across groups, and ensure that results are easy to interpret for both technical and non-technical users.

1. KPI Scorecards
    - Displays the average math score, average reading score, and average writing score.
    - Purpose: Provides a high-level snapshot of overall student performance and quickly highlights which subjects are generally stronger or weaker.
2. Pie Chart – Proportion of Students Scoring Over 80% by Gender
    - Shows the percentage of male and female students who achieved an average total score above 80%.
    - Purpose: Helps identify gender distribution among high-performing students and highlights potential performance gaps between groups.
3. Scatter Plot – Average Score vs Total Score
    - Plots average overall score against total score for each student.
    - Purpose: Illustrates the relationship between overall performance metrics and helps detect patterns, clustering, or outliers in scoring consistency.
4. Histogram – Average Overall Score
    - Visualizes the distribution of average scores across all students.
    - Purpose: Provides insight into score spread, clustering, and overall performance levels within the dataset.
5. Histograms – Average Scores by Subject and Group
    - Includes histograms for average scores of each subject by gender, as well as by test preparation status.
    - Purpose: Highlights performance differences across demographic and preparatory groups and helps assess the impact of test preparation courses on student outcomes.
6. Bar Chart – Average Total Score by Parental Education Level
    - Displays the average total score grouped by parental educational attainment.
    - Purpose: Reveals trends in student performance based on parental education, offering insights into potential socio-educational influences.
7. Stacked Bar Chart – Gender Distribution by Test Preparation
    - Shows test preparation status (Completed vs None) with bars stacked by gender.
    - Purpose: Visualizes participation in test preparation courses and compares gender balance within each preparation category, complementing performance-focused analyses with participation context.
8. Box Plots (Whisker Plots) – Subject Scores Grouped by Gender
    - Displays score distributions (minimum, quartiles, median, and maximum) for math, reading, and writing, grouped by gender.
    - Purpose: Provides a clear view of score variability and dispersion, highlights differences between groups, and identifies students with exceptionally high or low performance.
9. Top 10 Highest-Scoring Students Table
    - Presents the top 10 students based on total score, including key attributes such as gender, parental education level, and test preparation status.
    - Purpose: Highlights exceptional performers and provides contextual information to better understand factors associated with high achievement.
10. Score Distribution Table – Histogram Values
    - Displays the score ranges and corresponding number of students used in the histogram of average overall scores.
    - Purpose: Ensures clarity and accessibility by explicitly stating the frequency values behind the histogram, especially since data labels cannot be directly added to histogram charts in Google Sheets.
11. Candlestick Chart Summary Table
    - Lists the minimum, first quartile (Q1), third quartile (Q3), and maximum values used to construct the candlestick (box plot) charts.
    - Purpose: Improves readability and transparency by allowing users to easily interpret the statistical values underlying the box plots without relying solely on visual estimation.

Each visualization and table was carefully selected to support trend identification, group comparison, and actionable insight generation, making the dashboard both an effective analytical tool and a clear, user-friendly presentation asset for stakeholders.

<img width="602" height="754" alt="Screenshot 2025-12-31 at 21 32 20" src="https://github.com/user-attachments/assets/c0150616-349e-4b70-8098-14db0bb742aa" />

---

## Instructions to Run or View
This project is fully implemented using Google Sheets for data preparation and visualization, and Google Slides for presenting insights. No additional software installation is required.

1. Access the Google Sheets Dataset
    - Open the provided Google Sheets link (https://docs.google.com/spreadsheets/d/1r0C_Cq4M3NB3iwOiCqIWITYsfCC-ku3whXtb-oZIYSg/edit?usp=sharing).
    - Review the dataset, including the cleaned and transformed columns such as total scores, average scores, and student IDs.
2. Explore the Dashboard Visualizations
    - All charts and graphs are available within Google Sheets.
    - You can filter, sort, or interact with the data to explore trends, distributions, and comparisons across variables such as gender, parental education level, and test preparation course.
3. View the Presentation Slides
    - Open the Google Slides link to view the slides summarizing the analysis and insights (https://docs.google.com/presentation/d/1tEpJf4lAY7cy1OqFZTmpBzTs8IogCdQdD-R6uWNtI3w/edit?usp=sharing).
    - The slides highlight key trends, top-performing students, and visual summaries suitable for stakeholders.

---

## Key Findings 
**Overall Academic Performance**
- Average scores are moderate across all subjects.
- Reading (69.17) is the strongest subject, followed by writing (68.05) and math (66.09).
- Math appears to be the most challenging subject overall.

**Score Distribution**
- Most students score in the mid-range (61–80):
    - 61–70: 245 students
    - 71–80: 240 students
- Fewer students achieve high scores:
    - 81–90: 129 students
    - 91–100: 46 students
- 109 students score below 50, indicating a group that may need additional support.

**High Performers by Gender**
- Among students scoring above 80 (average total score):
    - Female students: 59.3% (115 students)
    - Male students: 40.7% (79 students)
- Female students are more represented among high achievers.

**Gender Differences by Subject**
- Male students perform better in math (68.72 vs 63.63).
- Female students outperform males in reading and writing:
    - Reading: 72.60 vs 65.47
    - Writing: 72.46 vs 62.31
- Indicates subject-specific strengths by gender.

**Score Variability (Box Plot / Candlestick Analysis)**
- Math scores:
    - Males show wider variability and higher median (69).
    - Females show more consistency but a slightly lower median (65).
- Reading scores:
    - Female students have higher medians (73 vs 66) and higher upper quartiles.
    - A larger proportion of female students achieve high reading scores.

**Test Preparation Participation**
- Test prep participation is balanced across genders:
    - Completed: 184 females, 174 males
    - Not completed: 334 females, 308 males
- Gender does not significantly affect participation rates.

**Impact of Test Preparation**
- Students who completed test prep score higher across all subjects:
    - Math: 69.69 vs 64.07
    - Reading: 73.89 vs 66.53
    - Writing: 74.41 vs 64.50
- Test preparation is strongly associated with improved performance.

**Top 10 Highest-Achieving Students**
- 7 out of 10 are female.
- 3 did not complete test preparation, showing high achievement is still possible without it.
- Bachelor’s degree is the most common parental education level among top performers.

**Average Score vs Total Score**
- Scatter plot shows a strong, positive linear relationship.
- Indicates consistent performance across subjects with no anomalies or outliers.
- Confirms reliability of the scoring structure.

**Performance by Parental Education Level**
- Higher parental education is associated with higher student scores:
    - Master’s degree: 73.59
    - Bachelor’s degree: 71.92
- Lower averages observed for high school or some high school education.
- Suggests socio-educational background may influence outcomes.

**Conclusion / Synthesis of Key Findings**
Overall, the dashboard reveals clear patterns in student performance influenced by gender, test preparation, and parental education level. 
- Female students tend to excel in language-based subjects and are more prevalent among high achievers, while male students show stronger performance in math but greater score variability.
- Test preparation consistently correlates with higher scores across all subjects, highlighting its positive impact.
- Additionally, students from higher parental education backgrounds generally achieve better outcomes.
- Together, these insights demonstrate how academic performance is shaped by a combination of demographic, preparatory, and socio-educational factors, underscoring the value of data-driven analysis in understanding student achievement.

---

## Future Improvements 
While the current dashboard provides a comprehensive overview of student performance, there are several opportunities for future enhancement to further deepen insights and improve usability:

1. Advanced Interactivity
    - Introduce interactive filters or slicers (e.g., by gender, parental education level, or test preparation status) to allow users to dynamically explore specific subgroups within the dataset.
2. Enhanced Visualization Tools
    - Migrate or replicate the dashboard in a dedicated BI tool such as Looker Studio or Tableau to enable more advanced chart customization, improved interactivity, and better control over visual styling (e.g., box plot coloring and tooltips).
3. Expanded Performance Metrics
    - Incorporate additional KPIs such as pass/fail rates, subject-specific improvement gaps, or percentile rankings to provide more nuanced measures of student performance beyond averages and totals.
4. Deeper Statistical Analysis
    - Add statistical testing or modeling (e.g., correlation analysis, regression, or variance analysis) to quantify the strength of relationships between performance outcomes and factors such as test preparation or parental education.
5. Time-Based or Comparative Analysis
    - If longitudinal or multi-cohort data becomes available, extend the analysis to compare performance trends over time or across different student groups or academic periods.
6. Improved Accessibility and Usability
    - Enhance dashboard readability by adding explanatory tooltips, annotations, and brief insight summaries directly within the dashboard to support non-technical stakeholders.

These improvements would help transform the dashboard from a descriptive analytics tool into a more interactive, scalable, and decision-support-oriented solution, while building on the strong analytical foundation established in this project.
