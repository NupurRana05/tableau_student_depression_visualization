Tableau – Student Depression Visualization Project

# Introduction

In this project, I analyzed student depression data to understand the mental health condition of students and identify the major factors affecting depression.
The main objective of this project is to extract insights from data using visualization so that patterns related to academic pressure, financial stress, sleep duration, study hours, dietary habits, gender, and suicidal thoughts can be clearly understood.

For analysis, I first loaded the dataset into SQL, performed data cleaning and transformation, and then connected the cleaned data to Tableau for visualization.
I created five different charts and combined them into a single interactive dashboard to present insights in a clear and meaningful way.

# Tools & Technologies Used

SQL – Data cleaning, transformation, and grouping

Tableau – Data visualization and dashboard creation

Excel / CSV – Dataset storage (source format)

Data Pre-Processing (SQL Work)

Before visualization, I performed the following steps in SQL:

Loaded the dataset into SQL Server

Used GROUP BY queries to aggregate data

Updated gender values:

Male → M

Female → F

Created a new Index column for easy reference

Created Age Group columns (example: 18–20, 21–23, 24+)

Cleaned inconsistent and duplicate values

After preprocessing, the data was connected to Tableau.

# Explain each Charts/Graph/plot

1. Count of Students by Suicidal Thoughts (Gender-wise)

 Chart Type: Stacked Bar Chart

 Objective:

 To analyze suicidal thoughts among students based on gender.

 Insights:

 Both male and female students show suicidal thoughts

 Students with depression have a higher count of suicidal thoughts

 Gender-based mental health risk can be clearly identified

2. Students by Financial Stress (Age Group-wise)

 Chart Type: Horizontal Bar Chart / Heat-style bars

 Objective:

 To understand how financial stress affects different age groups.

 Insights:

 Financial stress increases with age

 Senior students face more financial pressure

 Financial stress is a major contributor to depression

3. Academic Pressure by Sleep Duration

 Chart Type: Area Chart

 Objective:

 To analyze the relationship between sleep duration and academic pressure.

 Insights:

 Less sleep leads to higher academic pressure

 Students sleeping fewer hours show more stress

 Proper sleep plays an important role in mental health

4. Age by Depression-wise Dietary Habits

 Chart Type: Heatmap

 Objective:

 To analyze dietary habits based on age and depression level.

 Insights:

 Students with unhealthy diets show higher depression

 Healthy dietary habits are more common in low-depression students

 Diet has a strong impact on mental health

5. Students by Academic Pressure-wise Study Hours

 Chart Type: Line Chart

 Objective:

 To understand how study hours change with academic pressure.

 Insights:

 Higher academic pressure results in longer study hours

 Excessive study hours increase stress and depression risk

 Balanced study time is important for mental well-being

# Dashboard Objective

The dashboard provides a complete overview of student mental health by combining:

Academic pressure

Financial stress

Sleep duration

Study hours

Dietary habits

Gender and age analysis

It helps in early identification of depression patterns among students.

# Conclusion

This project shows that academic pressure, financial stress, poor sleep, unhealthy diet, and excessive study hours are major factors contributing to student depression.
Using SQL for data processing and Tableau for visualization, I successfully extracted meaningful insights that can help educational institutions and counselors take preventive actions.














