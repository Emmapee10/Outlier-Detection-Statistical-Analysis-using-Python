Outlier Detection & Statistical Analysis using Python
Overview
This project explores one of the most important concepts in data analysis and statistics: Outlier Detection.
Using Python and statistical techniques, I analysed height distribution data to identify abnormal observations, understand data spread, and visualise how statistical models behave in real datasets.
The project combines:


Mathematics


Statistics


Data Analysis


Scientific Computing


Visualisation


to demonstrate how raw data can be transformed into meaningful insight.

What This Project Covers
This notebook walks through a practical statistical workflow involving:


Data loading and preprocessing


Exploratory Data Analysis (EDA)


Histogram visualisation


Normal distribution analysis


Standard deviation calculations


Outlier detection using:


3 Standard Deviations Rule


Z-Score Method




Removing outliers from datasets


Statistical interpretation of data distributions



Motivation
Outliers can significantly distort:


statistical models,


machine learning predictions,


averages,


variance,


and overall data interpretation.


The goal of this project was not just to detect unusual values, but to understand why they occur and how statistical theory applies to real-world datasets.
As someone with a strong foundation in Applied Mathematics, I enjoy bridging theoretical concepts with computational implementation — turning formulas into working analytical systems.
This notebook reflects that approach.


Key Concepts Applied

Statistical Concepts


Mean


Standard Deviation


Gaussian (Normal) Distribution


Probability Density


Z-Score Analysis


Distribution Behaviour


Python & Data Science Tools


Python


Pandas


NumPy


Matplotlib


SciPy



Visualisation & Analysis
The project includes:


Histogram plotting


Distribution curve visualisation


Density estimation


Statistical range calculations


Identification of extreme values


Using graphical analysis alongside mathematical reasoning helped reveal how the dataset behaves under normal distribution assumptions.

Outlier Detection Methods Used
1. Three Standard Deviations Rule
Outliers were detected using:
μ±3σ\mu \pm 3\sigmaμ±3σ
Where:


μ\muμ = Mean


σ\sigmaσ = Standard Deviation


Any data point outside this interval was treated as an outlier.

2. Z-Score Method
Each observation was standardised using:
z=x−μσz = \frac{x - \mu}{\sigma}z=σx−μ​
Observations with:


z>3z > 3z>3


or z<−3z < -3z<−3


were classified as outliers.
This method provides a standardised way to measure how far a value deviates from the mean.

What I Learned
Through this project, I strengthened my understanding of:


statistical thinking,


exploratory data analysis,


computational statistics,


and the relationship between mathematical theory and practical implementation.


More importantly, it reinforced the importance of clean data in analytics and machine learning workflows.

Why This Project Matters
Data is rarely perfect.
Real-world datasets often contain:


noise,


anomalies,


inconsistencies,


and unexpected behaviour.


Understanding how to identify and handle outliers is a foundational skill in:


Data Science


Artificial Intelligence


Predictive Analytics


Statistical Modelling


Research Computing


This project represents an important step in my journey toward building intelligent, mathematically grounded analytical systems.

About Me
I am passionate about:


Applied Mathematics


Data Analytics


Artificial Intelligence


Scientific Computing


Numerical Methods


Research & Problem Solving


I enjoy building projects that combine mathematics, computation, and real-world insight.

Final Note
This notebook is more than a coding exercise.
It is an exploration of how mathematics, statistics, and programming come together to uncover patterns hidden inside data.
And this is only the beginning. 