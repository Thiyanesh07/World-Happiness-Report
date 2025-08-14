🌏 World Happiness Report Analysis

📌 Project Overview

This project analyzes the World Happiness Report dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.
We explore global happiness trends, perform statistical and linear algebra operations, and extract insights into the factors that contribute to happiness worldwide.

The analysis is divided into 8 parts:

Basic Data Understanding

Exploratory Data Analysis (EDA)

Statistics

Linear Algebra & NumPy

Calculus

Feature Engineering

SQL Simulation in Pandas

Insights



📂 Dataset

Source: World Happiness Report

Typical Columns:

Country – Country name

Region – Region grouping

Ladder score – Happiness score (0–10 scale)

Logged GDP per capita – Economic wealth indicator

Social support – Measure of social connections

Healthy life expectancy – Life expectancy in years

Generosity – Willingness to help others

Perceptions of corruption – Public perception of corruption




📊 Part 1 – Basic Data Understanding

Load and preview dataset (first 10 rows)

Dataset shape, column names, and data types

Missing values and duplicate checks

Summary statistics (.describe())

Count of unique countries and regions

Country with the highest happiness score

Most common region




📈 Part 2 – Exploratory Data Analysis (EDA)

Histogram of happiness scores

Top 10 happiest countries

Bottom 10 countries by happiness

Average happiness score per region (bar chart)

GDP per capita vs happiness score (scatter plot)

Boxplot of happiness scores grouped by region

📐 Part 3 – Statistics

Mean, median, and mode of Ladder score

Variance and standard deviation

Percentage of countries below global average

Most common region among top 20 happiest countries




➗ Part 4 – Linear Algebra & NumPy

Create arrays for Ladder score and Logged GDP per capita

Vector addition, subtraction, and dot product

Matrix multiplication: [GDP per capita, Social support] × [0.5, 0.5]

Normalization of Ladder score array




🔢 Part 5 – Calculus


Wellbeing_Index=(GDP×Happiness)+0.5×(Happiness−5)**2





🛠 Part 6 – Feature Engineering

is_happy → 1 if happiness score > 7 else 0

happiness_rank → Ranking based on descending Ladder score

above_average_gdp → 1 if GDP > global mean

Quartiles for Healthy life expectancy




💾 Part 7 – SQL Simulation in Pandas

Countries with happiness score > 7

Sort by GDP per capita (descending)

Group by region → average happiness score

Top 5 regions by average happiness score

Select countries with life expectancy > 70





💡 Part 8 – Insights

Happiest country

Happiest region (on average)

GDP–Happiness correlation

Do richer countries always score higher in happiness?

Region with the highest average life expectancy





🛠 Tools & Libraries Used

Python 3.x

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Visualization

Jupyter Notebook – Interactive analysis





📌 How to Run

git clone https://github.com/yourusername/world-happiness-analysis.git

pip install pandas numpy matplotlib seaborn jupyter

jupyter notebook
