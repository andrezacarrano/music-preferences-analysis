
# 🎵 Music Preferences Analysis: Springfield vs. Shelbyville

## 📌 Project Overview

This project analyzes and compares the music listening preferences of users from Springfield and Shelbyville.

The main objective is to investigate whether user activity differs depending on the day of the week and the city.

From a business perspective, understanding these behavioral patterns can help music streaming platforms identify differences in user engagement and support more targeted marketing campaigns and service personalization strategies.

## 🎯 Business Questions

- Does music listening activity differ between Springfield and Shelbyville?
- Are there specific days of the week with higher listening activity?
- Do users from both cities demonstrate similar listening patterns?

## 📊 Key Findings

The analysis revealed differences in music listening activity across the two cities and days of the week.

**Listening activity by city:**
- Springfield: 42,741 tracks played.
- Shelbyville: 18,512 tracks played.

Springfield recorded a higher volume of listening activity than Shelbyville.

**Listening activity by day of the week:**
- Friday: 21,840 tracks played.
- Monday: 21,354 tracks played.
- Wednesday: 18,059 tracks played.

Friday recorded the highest listening activity among the days presented.

These findings suggest differences in user engagement across cities and weekdays. They may provide useful insights for developing targeted marketing campaigns and improving user engagement strategies.

*Note: These findings are based on descriptive analysis. Formal statistical testing would be required to determine whether the observed differences are statistically significant.*

## 🛠️ Tools & Technologies

- **Python:** Main programming language.
- **Pandas:** Data cleaning, manipulation, aggregation, and analysis.
- **Jupyter Notebook:** Interactive development and documentation of the analysis.

## 🔍 Methodology

### 1. Data Overview

- Loaded the CSV dataset.
- Inspected data types and dataset structure.
- Identified missing values and duplicate records.

### 2. Data Preprocessing

- Standardized column names using the `snake_case` convention.
- Handled missing values according to the context of each column.
- Removed explicit duplicate records.
- Identified and corrected implicit duplicates in music genre names using custom functions.

### 3. Exploratory Data Analysis

- Grouped listening activity by city and day of the week.
- Calculated the number of tracks played.
- Compared listening activity across the two cities and different weekdays.

### 4. Hypothesis Investigation

Investigated whether listening activity varied depending on the city and day of the week by comparing aggregated listening data.

## 💡 Skills Developed

Through this project, I developed practical skills in:

- **Data Cleaning:** Handling missing values, removing duplicates, and correcting inconsistent categorical values.
- **Data Manipulation:** Using Pandas for filtering, grouping, and aggregation.
- **Exploratory Data Analysis (EDA):** Identifying patterns and comparing user behavior across different segments.
- **Data Interpretation:** Translating aggregated data into business-oriented insights.
- **Notebook Organization:** Structuring Jupyter Notebook workflows for clarity and reproducibility.

## 🚀 How to Run the Project

1. Make sure Python 3.x is installed.
2. Install Pandas:

   ```bash
   pip install pandas
   ```

3. Open the notebook using VS Code with the Jupyter extension, Jupyter Notebook, or JupyterLab.
4. Make sure the dataset `music_project_en.csv` is located in the same directory as the notebook.
5. Run the notebook cells sequentially, starting with the library imports and data loading steps.

## 🔮 Future Improvements

- Apply formal statistical tests, such as t-tests or ANOVA, to evaluate whether the observed differences are statistically significant, where appropriate.
- Add data visualizations using Matplotlib or Seaborn to improve the presentation of listening patterns.
- Expand the analysis to investigate music genre preferences by city and day of the week.
- Incorporate additional data sources to develop a broader understanding of user listening behavior.
- Automate data preprocessing through reusable and modular scripts.

---

**Project Focus:** Data Cleaning | Exploratory Data Analysis | Python | Pandas | Hypothesis Investigation
