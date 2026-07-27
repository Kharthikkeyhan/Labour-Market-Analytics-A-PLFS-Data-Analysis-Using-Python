# 📊 Labour Market Analytics: A PLFS Data Analysis Using Python

> **An end-to-end Python data analytics project analyzing the Periodic Labour Force Survey (PLFS) "Persons Surveyed" dataset (2018–2024) to uncover survey coverage patterns, demographic composition, and state-wise trends across India.**

---

## 📖 Project Description

The **Periodic Labour Force Survey (PLFS)**, conducted by the **Ministry of Statistics and Programme Implementation (MoSPI), Government of India**, is one of India's primary surveys for collecting labour force statistics. This project focuses on analyzing the **Persons Surveyed** dataset (2018–2024) using Python to understand survey coverage, demographic composition, and sampling consistency across states, union territories, and survey quarters.

The project follows a complete **Data Analytics Lifecycle**, including:

- 📥 Data Collection
- 🧹 Data Cleaning & Preprocessing
- ⚙️ Feature Engineering
- 📊 Exploratory Data Analysis (EDA)
- 📈 Statistical Analysis
- 📉 Data Visualization
- 💡 Business Storytelling & Insights

The analysis transforms raw government survey data into meaningful insights that support policymakers, researchers, and labour market analysts in evaluating survey quality and understanding demographic trends.

---

# 🎯 Business Problem

Government agencies collect large volumes of labour market survey data every quarter. However, raw datasets alone do not provide actionable insights for decision-making. Variations in survey coverage across states, years, and demographic groups often remain hidden without systematic analysis.

This project addresses these challenges by:

- Understanding survey implementation across India.
- Evaluating demographic representation.
- Comparing survey intensity across states and years.
- Identifying trends, patterns, and outliers.
- Presenting findings using statistical analysis and interactive visualizations.

---

# 🎯 Project Objectives

- Analyze year-wise trends (2018–2024) in the number of persons, households, and survey blocks.
- Compare state-wise survey coverage to identify regions with the highest and lowest participation.
- Examine quarterly survey coverage across all PLFS survey rounds.
- Analyze demographic distribution by age group and gender.
- Identify year-wise and state-wise trends, patterns, and outliers.
- Present analytical findings through statistical analysis and visualization.

---

# 🗂 Dataset Information

| Property | Details |
|----------|---------|
| **Dataset** | PLFS Persons Surveyed |
| **Source** | Ministry of Statistics and Programme Implementation (MoSPI) |
| **Portal** | India Data Portal (Open Government Data) |
| **File Format** | CSV |
| **Number of Records** | 529 |
| **Original Features** | 24 |
| **Timeline** | 2018–2024 |
| **Coverage** | 22 States/UTs + All India |

### Dataset Includes

- Number of Survey Blocks
- Number of Households Surveyed
- Number of Persons Surveyed
- Gender Distribution
- Age-wise Population Distribution
- State Information
- Quarterly Survey Information

---

# 📋 Dataset Features

The dataset contains **24 original variables**, grouped into the following categories.

## Survey Information

- Year
- Quarter
- State Name
- State Code

## Survey Coverage

- Number of Blocks Surveyed
- Households Surveyed

## Demographic Variables

### Age Group (0–4 Years)

- Male
- Female
- Persons

### Age Group (5–14 Years)

- Male
- Female
- Persons

### Age Group (15–29 Years)

- Male
- Female
- Persons

### Age Group (15–59 Years)

- Male
- Female
- Persons

### Age Group (15 Years & Above)

- Male
- Female
- Persons

### Overall Population

- Total Males
- Total Females
- Total Persons

---

# 🛠 Technologies Used

## Programming Language

- Python

## Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Development Environment

- Google Colab

---

# 🧹 Data Preprocessing

Before analysis, the dataset underwent comprehensive preprocessing.

### Data Cleaning

- Verified dataset structure
- Checked data types
- Identified missing values *(None found)*
- Checked duplicate records *(None found)*
- Standardized state names
- Standardized quarter labels
- Converted survey count columns into integer data type
- Validated dataset consistency

---

# ⚙️ Feature Engineering

To enhance analytical capability, several new variables were created.

| Feature | Purpose |
|----------|---------|
| **is_all_india** | Separate national aggregate from state records |
| **period_date** | Create time-series analysis |
| **fiscal_quarter** | Financial reporting |
| **period_label** | Improved visualization |
| **persons_per_household** | Average household size |
| **households_per_block** | Survey efficiency |
| **persons_per_block** | Survey density |
| **sex_ratio_all_ages** | Gender balance |
| **share_working_age_15_59** | Working-age population analysis |
| **male_share_pct** | Male participation percentage |
| **female_share_pct** | Female participation percentage |

---

# 📊 Exploratory Data Analysis (EDA)

## 1️⃣ Univariate Analysis

Analyzed the distribution of individual variables using:

- Histogram
- Box Plot
- Count Plot

Focus Areas:

- Distribution of Persons Surveyed
- Households Surveyed
- Survey Quarter Frequency

---

## 2️⃣ Bivariate Analysis

Studied relationships between two variables using:

- Line Plot
- Scatter Plot
- Bar Chart
- Correlation Heatmap

Key Analyses:

- Year vs Persons per Block
- Male vs Female Population
- Working-age Population Share
- Correlation Analysis

---

## 3️⃣ Multivariate Analysis

Examined relationships among multiple variables using:

- Pair Plot
- Bubble Scatter Plot
- Grouped Bar Analysis
- Pivot Table Heatmaps
- Grouped Box Plot
- Correlation Heatmap (Original + Engineered Features)

---

# 📈 Statistical Analysis

The following statistical techniques were applied:

### Measures of Central Tendency

- Mean
- Median
- Mode

### Distribution Analysis

- Histogram
- Skewness

### Correlation Analysis

- Pearson Correlation Matrix

### Key Observation

The distribution of persons surveyed is **positively skewed**, primarily because a few observations (such as **All-India aggregate records**) contain much higher survey counts than individual state-level observations.

---

# 📊 Key Findings

- Survey coverage remained relatively stable between **2018 and 2024**.
- Households, persons surveyed, and survey blocks exhibit **strong positive correlations**.
- The **15–59 years** working-age population consistently represents the largest share of surveyed individuals.
- Male and female participation remains proportionally balanced.
- Household size varies across states, highlighting regional demographic differences.
- Quarterly survey implementation shows consistent coverage with only minor seasonal variation.

---

# 📌 Types of Analysis

## 📄 Descriptive Analysis

Summarizes historical survey coverage across years, states, and quarters.

---

## 🔍 Diagnostic Analysis

Explains reasons behind observed survey variations.

---

## 📈 Predictive Analysis

Forecasts future survey coverage and demographic trends.

---

## 🎯 Prescriptive Analysis

Provides recommendations to improve future survey planning and resource allocation.

---

# 🚀 Future Enhancements

Future scope of this project includes:

- Integrate Labour Force Participation Rate (LFPR)
- Integrate Worker Population Ratio (WPR)
- Integrate Unemployment Rate (UR)
- Apply Machine Learning for anomaly detection
- Develop interactive dashboards
- Enable State × Year × Quarter drill-down analysis
- Automate future PLFS report generation

---

# 🏆 Conclusion

This project demonstrates how Python can be effectively used to analyze large-scale government survey data. Through data preprocessing, feature engineering, exploratory data analysis, statistical analysis, and visualization, meaningful insights were extracted regarding survey coverage, demographic composition, and regional patterns across India.

The project provides valuable information for policymakers and researchers while establishing a strong foundation for future labour market analytics using additional PLFS employment indicators.

---


---

ject helpful, please consider giving it a Star!
