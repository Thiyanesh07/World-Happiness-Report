# 🌏 World Happiness Report – Data Analysis



## 📖 Overview
This project analyzes the **World Happiness Report** dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.  
We explore patterns, correlations, and insights into factors affecting global happiness.

---

## 📂 Dataset Information
**Source:** [World Happiness Report](https://worldhappiness.report/)  
**Main Features:**
- `Country` – Country name
- `Region` – Geographic region
- `Ladder score` – Happiness score (0–10)
- `Logged GDP per capita`
- `Social support`
- `Healthy life expectancy`
- `Generosity`
- `Perceptions of corruption`

---

## 🗂 Project Structure

### **Part 1 – Basic Data Understanding**
- Load dataset, preview first 10 rows
- Dataset shape, column names, and data types
- Missing values & duplicates check
- Summary statistics
- Unique countries & regions count
- Country with **highest happiness score**
- Most common region

### **Part 2 – Exploratory Data Analysis (EDA)**
- Histogram of happiness scores
- Top 10 happiest & bottom 10 countries
- Average happiness score per region (bar chart)
- GDP per capita vs happiness score (scatter)
- Happiness score distribution by region (boxplot)

### **Part 3 – Statistics**
- Mean, median, mode of `Ladder score`
- Variance & standard deviation
- % of countries below global average
- Most common region in top 20 happiest countries

### **Part 4 – Linear Algebra & NumPy**
- Arrays for `Ladder score` & `GDP per capita`
- Vector addition, subtraction, dot product
- Matrix multiplication with weights `[0.5, 0.5]`
- Normalization of happiness scores

### **Part 5 – Calculus**
Formula:  
\[
Wellbeing\_Index = (GDP \times Happiness) + 0.5 \times (Happiness - 5)^2
\]  
Find derivative wrt **Happiness**.

### **Part 6 – Feature Engineering**
- `is_happy` → 1 if happiness score > 7 else 0
- `happiness_rank` (descending order)
- `above_average_gdp` → 1 if GDP > global mean
- Quartiles for `Healthy life expectancy`

### **Part 7 – SQL Simulation in Pandas**
- Countries with happiness score > 7
- Sort by GDP (desc)
- Group by region → avg happiness score
- Top 5 regions by happiness
- Countries with life expectancy > 70

### **Part 8 – Insights**
- Happiest country & region
- GDP–Happiness correlation
- Do richer countries always score higher?
- Region with highest life expectancy

---

## 🛠 Tech Stack
| Tool / Library   | Purpose |
|------------------|---------|
| Python 3.x       | Main language |
| Pandas           | Data manipulation |
| NumPy            | Numerical operations |
| Matplotlib       | Visualization |
| Seaborn          | Statistical plots |
| Jupyter Notebook | Interactive coding |

---

## 🚀 Getting Started
```bash
# Clone the repository
git clone https://github.com/yourusername/world-happiness-analysis.git

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Run the notebook
jupyter notebook
