# Task 5: Exploratory Data Analysis of the Titanic Dataset

## 📝 Project Overview

This project is a requirement for the Data Analyst Internship at **Elevate Labs**. The objective is to conduct an Exploratory Data Analysis (EDA) on the famous Titanic passenger dataset to uncover key patterns and insights related to the factors influencing passenger survival.

---

## 📊 Dataset

The analysis was performed on the Titanic dataset, which is available as a built-in dataset in the Seaborn library. This dataset contains demographic and travel information for each passenger, such as their age, sex, passenger class, and whether they survived the disaster.

---

## 🛠️ Tools Used

* **Programming Language:** Python
* **IDE:** Jupyter Notebook (JupyterLab)
* **Core Libraries:**
    * **Pandas:** For data manipulation and analysis.
    * **Matplotlib & Seaborn:** For data visualization.

---

## 📈 Analysis Process

The following steps were taken during the analysis:
1.  **Data Loading:** The dataset was loaded and inspected for an initial overview.
2.  **Data Inspection:** Functions like `.info()`, `.describe()`, and `.head()` were used to understand the data structure and identify missing values.
3.  **Categorical Variable Analysis:** Categorical features like passenger class (`class`) and gender (`sex`) were analyzed to understand their relationship with survival.
4.  **Numerical Variable Analysis:** Numerical features like age (`age`) and ticket fare (`fare`) were analyzed to understand their distributions.
5.  **Relationship Analysis:** A correlation heatmap was used to explore the relationships between different numerical variables.

---

## 💡 Key Findings & Insights

Several key insights were derived from the analysis:

* **Impact of Passenger Class:** The majority of passengers were in Third Class, and they had the lowest survival rate compared to First and Second Class passengers.
* **Impact of Gender:** Women had a significantly higher survival rate than men, reflecting the "women and children first" protocol during the evacuation.
* **Age Distribution:** Most passengers were young adults, primarily in the 20-35 age range. First-class passengers tended to be older on average.
* **Fare and Class Correlation:** A strong negative correlation was observed between passenger class and the fare paid; as the class number increased (i.e., from 1st to 3rd), the ticket price decreased.