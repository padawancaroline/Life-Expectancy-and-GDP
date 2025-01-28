# Life Expectancy and GDP Analysis

This project analyzes the relationship between **life expectancy** and **GDP** across six countries between 2000 and 2015. Using data from the **World Health Organization** and the **World Bank**, the analysis provides insights into how economic growth correlates with health outcomes globally.

Findings were shared in a [Blog Post](https://medium.com/@caroline.orlianges/unearthing-the-trends-how-gdp-and-life-expectancy-evolved-across-nations-9c90f86c1c64) on Medium

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Details](#dataset-details)
3. [Goals and Key Questions](#goals-and-key-questions)
4. [Analysis Steps](#analysis-steps)
5. [How to Run the Notebook](#how-to-run-the-notebook)
6. [Dependencies](#dependencies)
   
---

## Project Overview
This project explores:
- The evolution of **life expectancy** and **GDP** across six countries (2000-2015).
- The correlation between economic growth and health outcomes.
- Country-specific patterns and trends in life expectancy and GDP.

The notebook includes exploratory data analysis (EDA), visualizations, and statistical testing to provide actionable insights.

---

## Dataset Details
- **Source**: World Health Organization (WHO) and World Bank.
- **File Used**: `all_data.csv` (provided in this repository).
- **Variables**:
  - `Country`: Name of the country.
  - `Year`: Year of observation (2000-2015).
  - `Life Expectancy`: Average life expectancy in years.
  - `GDP`: Gross Domestic Product in USD.

---

## Goals and Key Questions
1. How have **life expectancy** and **GDP** changed over time in these countries?
2. Is there a significant **correlation** between GDP and life expectancy?
3. How do trends in life expectancy and GDP vary across countries?

---

## Analysis Steps
The analysis is divided into the following steps:
1. **Data Import and Cleaning**:
   - Load the dataset and handle missing values.
   - Format variables for consistency.
2. **Exploratory Data Analysis (EDA)**:
   - Summary statistics of life expectancy and GDP.
   - Visualization of trends over time.
3. **Trends Over Time**:
   - Line charts showing GDP and life expectancy trends.
   - Comparative analysis across countries.
4. **Correlation Analysis**:
   - Statistical correlation between GDP and life expectancy.
   - Scatterplots with trendlines to illustrate relationships.
5. **Conclusion**:
   - Summarize findings and insights.

---

## How to Run the Notebook

### 1. Clone the Repository
Use the following command to clone the repository:
```bash
git clone https://github.com/your-username/Life-Expectancy-and-GDP.git
cd Life-Expectancy-and-GDP
```

### 2. Install Dependencies
Ensure you have Python 3.8+ installed. Install the required libraries using:
```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook
Open the Jupyter Notebook using:
```bash
jupyter notebook Life-Expectancy-and-GDP.ipynb
```

### 4. Execute the Cells
Run each cell in the notebook sequentially to reproduce the analysis.

---

## Dependencies

The following Python libraries are required:
- `pandas`: For data manipulation.
- `numpy`: For numerical calculations.
- `matplotlib`: For creating visualizations.
- `seaborn`: For enhanced and detailed visualizations.

Install them with:
```bash
pip install pandas numpy matplotlib seaborn
```
 
