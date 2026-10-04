# Global Happiness: Advanced Data Visualization and Storytelling with Python

## 📌 Project Overview

This project explores the **World Happiness Report 2019 dataset** using Python to understand happiness scores across countries and their relationships with economic, social, and health-related factors.

The project demonstrates how data visualization and storytelling can transform raw data into meaningful insights. Six visualizations are created to identify patterns, compare countries, and explore relationships between different indicators of happiness.

## 🎯 Objectives

* Analyze the distribution of happiness scores across countries.
* Explore the relationship between GDP per capita and happiness.
* Compare countries with the highest and lowest happiness scores.
* Examine correlations among numerical variables.
* Visualize multiple happiness-related factors together.
* Communicate data-driven findings through charts and explanations.

## 📊 Dataset Description

The project uses the **World Happiness Report 2019 dataset**, containing 156 country or region records and 9 columns after data cleaning.

The dataset includes the following variables:

* Overall rank
* Country or region
* Score
* GDP per capita
* Social support
* Healthy life expectancy
* Freedom to make life choices
* Generosity
* Perceptions of corruption

## 🛠️ Technologies Used

* **Python** — Programming language for data analysis
* **Pandas** — Data loading and manipulation
* **NumPy** — Numerical computing
* **Matplotlib** — Data visualization
* **Seaborn** — Statistical visualization
* **Jupyter Notebook** — Interactive analysis environment
* **python-docx** — Automated Word report generation

## 📈 Visualizations Created

The project includes six visualizations:

1. **Happiness Score Distribution:** Examines the distribution of happiness scores across countries.
2. **GDP per Capita vs Happiness:** Explores the association between economic conditions and happiness scores.
3. **Top 15 Happiest Countries:** Compares countries with the highest happiness scores.
4. **Correlation Heatmap:** Shows correlations among numerical variables.
5. **15 Countries with the Lowest Happiness Scores:** Compares countries at the lower end of the happiness rankings.
6. **Multifactor Analysis:** Uses a bubble chart to explore GDP per capita, happiness, social support, and healthy life expectancy together.

All visualizations are saved as high-resolution PNG images in the `visualizations` folder.

## 🔍 Data Analysis Workflow

1. Load the dataset using Pandas.
2. Inspect the dataset structure and column names.
3. Remove extra whitespace from column names.
4. Remove duplicate records.
5. Check for missing values.
6. Create visualizations using Matplotlib and Seaborn.
7. Interpret the charts and calculate selected correlations.
8. Generate a structured Word report containing the visualizations, explanations, findings, and conclusion.

## 📂 Project Structure

```text
Week2_DataVisualization_Project/
│
├── data/
│   └── happiness.csv
│
├── notebooks/
│   └── Week2_Advanced_Data_Visualization.ipynb
│
├── visualizations/
│   ├── 01_happiness_distribution.png
│   ├── 02_gdp_vs_happiness.png
│   ├── 03_top_happiest_countries.png
│   ├── 04_correlation_heatmap.png
│   ├── 05_lowest_happiness_scores.png
│   └── 06_multifactor_analysis.png
│
├── report/
│   └── Week2_Advanced_Data_Visualization_Report.docx
│
└── README.md
```

## 💡 Key Insights

The analysis investigates how happiness scores vary across countries and how they are associated with GDP per capita, social support, and healthy life expectancy.

The visualizations help identify the distribution of scores, differences between higher- and lower-ranked countries, and relationships among numerical indicators. The correlation analysis provides additional evidence about the strength and direction of linear associations.

The exact findings should be interpreted using the values and patterns displayed in the generated charts and calculated statistics. Correlation does not necessarily imply causation.

## 📄 Project Report

A detailed Word report is generated automatically and saved in the `report` folder. It includes:

* Introduction and objectives
* Dataset description
* Data analysis methodology
* Six visualizations with captions and interpretations
* Key findings and correlation values
* Implications and limitations
* Conclusion

## ▶️ How to Run the Project

1. Install Python 3 and Jupyter Notebook.

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly jupyter python-docx openpyxl
   ```

3. Place the dataset in the `data` folder with the filename `happiness.csv`.

4. Open the notebook located in the `notebooks` folder.

5. Run the notebook cells in order.

6. Check the generated PNG files in the `visualizations` folder.

7. Open the Word report in the `report` folder.

**Note:** The notebook uses relative paths, so run it from the expected project folder structure.

## ⚠️ Limitations

* The analysis focuses on the 2019 dataset and does not establish changes over time.
* Correlations show associations rather than causal relationships.
* The dataset's indicators may not represent every aspect of happiness or well-being.
* Findings should be interpreted in the context of the available data.

## 🏁 Conclusion

This project demonstrates the use of Python libraries for data cleaning, exploratory analysis, advanced visualization, and data storytelling. The six visualizations provide different perspectives on happiness scores and their relationships with economic, social, and health-related indicators.

By combining visual representations with statistical analysis and clear explanations, the project illustrates how data visualization can support better understanding and communication of complex datasets.

---

**Project:** Week 2 — Advanced Data Visualization and Storytelling with Python
**Domain:** Data Science and Exploratory Data Analysis
**Dataset:** World Happiness Report 2019
**Status:** Completed
