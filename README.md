Task 1: Data Visualization - Histogram of Age Distribution

Overview

This task is part of my Data Science internship at Prodigy InfoTech, where I worked on visualizing the distribution of the 'Age' column from a dataset using a histogram. The goal of this task was to practice data cleaning and analysis techniques while applying a visual representation to communicate insights effectively.

Objective

The main objective of this task was to:

Load, inspect, and clean the datasets to ensure they were ready for analysis.
Identify missing values and duplicated records.
Visualize the distribution of a numerical column ('Age') to gain insights into its distribution using a histogram.

Key Features of the Code

Data Loading: The datasets were loaded using Pandas.
Data Inspection: Performed preliminary inspection using .head(), .info(), and checked for missing values and duplicates with .isna().sum() and .duplicated().sum().
Visualization: A histogram was created using the ggplot package from plotnine to represent the distribution of the 'Age' column in the dataset.
Plot Display: The plot is saved to an in-memory buffer and displayed using Matplotlib.

Learning Outcomes

Understanding how to inspect and clean data (checking for missing and duplicate values).
Visualizing a numerical column using a histogram to observe its distribution.
Using Python libraries like Pandas, Plotnine, and Matplotlib for data analysis and visualization.
Learning to handle in-memory plotting and figure display using io for seamless image handling.

Tools & Technologies :

Python (Version 3.x)

Pandas (For data handling)

Plotnine (For creating the histogram)

Matplotlib (For displaying the image)

Numpy (For numerical operations)


Sample Output

The histogram generated from the 'Age' column provides a clear view of its frequency distribution, helping identify patterns and trends in the data.
