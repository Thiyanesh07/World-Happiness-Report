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
- <img width="861" height="679" alt="image" src="https://github.com/user-attachments/assets/7926b926-8018-4456-88ee-2b06de734ecc" />

- Top 10 happiest & bottom 10 countries
- Average happiness score per region (bar chart)
- GDP per capita vs happiness score (scatter)
- <img width="829" height="678" alt="image" src="https://github.com/user-attachments/assets/5733866a-4a57-4c22-b52b-998e24a28a09" />

- Happiness score distribution by region (boxplot)
- <img width="1428" height="707" alt="image" src="https://github.com/user-attachments/assets/b3abb097-788d-49e7-a9b6-832375ea5eb5" />


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
- <img width="840" height="564" alt="image" src="https://github.com/user-attachments/assets/e5cd3101-45f9-4186-a2c2-d5d80ce6ad68" />

- Do richer countries always score higher?
- Region with highest life expectancy
- Happiest on average
- <img width="871" height="184" alt="image" src="https://github.com/user-attachments/assets/6aa66ed4-527f-41e9-9f99-99a1263791e4" />
- <img width="939" height="686" alt="image" src="https://github.com/user-attachments/assets/f2cda4f6-70ef-4b11-98fc-627d1dfd9a38" />
- <img width="922" height="791" alt="image" src="https://github.com/user-attachments/assets/e673b853-5382-420f-b635-4b7087d869c3" />



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
