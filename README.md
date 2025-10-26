# 🩺 Global Cancer Survival Analysis

### Executive Summary:

This project analyzes global disparities in cancer survival rates using country-level demographic, socio-economic, and health data.
Data from WHO, World Bank, and GCO were processed and modeled in Python using K-means, Linear Regression, Random Forest, and XGBoost.
Findings highlight strong links between survival, income level, and healthcare investment, emphasizing global health inequalities. 
Based on these findings, I recommend the following actions to help improve global cancer outcomes:

1. Improve healthcare infrastructure and expand early detection programs.
2. Promote data-driven health policies tailored to each country’s context.
3. Strengthen international collaboration to ensure equitable access to cancer care.

#### Business Problem: 

Cancer survival rates vary widely across countries, reflecting inequalities in healthcare access and socio-economic conditions. These disparities challenge governments and international agencies in allocating resources effectively. This project explores which factors most influence survival globally and how data-driven insights can guide policies to reduce inequalities.

#### Methodology:

1. Data Collection & Preprocessing: Gathered country-level demographic, socio-economic, and cancer-related indicators from WHO, World Bank, GCO, and additional sources via web scraping; cleaned and prepared the data for analysis.
2. Exploratory Analysis & Visualization: Examined trends and patterns using descriptive statistics, correlation analysis, and geographic mapping.
3. Clustering: Applied K-means to group countries by income level and survival similarities to identify patterns and disparities.
4. Predictive Modeling: Built models using Linear Regression, Decision Trees, Random Forest, and XGBoost to determine factors influencing cancer survival rates.

#### Skills:

1. Data Collection & Web Scraping: Extracting and compiling data from multiple online sources.
2. Data Cleaning & Preprocessing: Handling missing values, transforming variables, and preparing datasets for analysis.
3. Exploratory Data Analysis (EDA): Visualizing trends, patterns, and correlations in complex datasets.
4. Machine Learning & Modeling: Applying regression, decision trees, Random Forest, XGBoost, and clustering algorithms.
5. Python Programming & Tools: Using Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Jupyter Notebooks.

#### Results & Business Recommendation:

This study identifies several factors influencing global cancer survival rates. Universal Health Coverage (UHC) strongly improves survival in low- and middle-income countries by increasing access to timely care, while its effect is smaller in high-income countries where coverage is already established. Access to treatments, such as radiotherapy, significantly enhances outcomes when combined with UHC, but misaligned investments can reduce efficiency. Healthcare infrastructure and medical staff reinforcement consistently improve survival across all countries, and high-quality cancer detection equipment further boosts outcomes, especially in low- and middle-income countries. Other critical factors include population size, integration of pain management, and coherent investment strategies.

I recommend these actions to ensure that investments and policies are effectively targeted to improve survival rates and reduce disparities across countries:

1. Improving UHC coverage and combining it effectively with treatment access.
2. Expanding public health centers and reinforcing medical staff.
3. Aligning investments with population needs to avoid inefficiencies.
4. Enhancing access to high-quality detection equipment and integrating it with care services.
5. Implementing coherent national strategies that include prevention, palliative care, and targeted resource allocation.

#### Next steps:

1. Incorporate patient-level data to personalize treatments and assess local policy impacts.
2. Use machine learning to capture complex interactions and improve predictions.
3. Evaluate country-specific interventions to identify best practices.
4. Strengthen collaboration among healthcare providers and agencies for coordinated cancer control.
